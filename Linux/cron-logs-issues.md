```
* * * * * user cmd  -- this works but 0 12 15 * * user cmd this not works
```
  - solution :- 
```
sudo service rsyslog restart
sudo service cron restart or sudo service crond restart


reference -: https://serverfault.com/questions/214234/crontab-not-running-at-specific-time-but-runs-every-min
```
