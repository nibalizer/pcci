pcci - puppet community continuous integration
==============================================


An experiment in public beaker testing


requirements:

* github bot account
* redis-server running
* beefy machine to run tests

A experimental instance is running at http://ci.puppet.community


application deployment:


right now this is super janky.


follow_pull_requests.py is run by 5 minute cron


4 run_worker.sh run (sent to background in shell)


one comment.py is run in the foreground in a tmux


improvement needed!
