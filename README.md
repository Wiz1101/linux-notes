# linux-notes
Notes for Linux


Linux distributions store the log files and directories in /var/log:

```shell
sudo tree /var/log -d -L 2
```

To count the number of failed logins using the given aureport command:
```shell
aureport -l | grep "no" | wc -l
```
