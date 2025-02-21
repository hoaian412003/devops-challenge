### Scenarios

- Memory leaks due to connection: we can facing with large connection are connected on nginx.
  - To check that issue use command ```ps aux | grep nginx```, this command will get list of process of nginx.
- Check the nginx log
  - It default on paths: `/var/log/nginx/error.log`, `/var/log/nginx/access.log`
- Check system log
  - Deamon of nginx also give a large of log: `/var/log/syslog`, `journalctl -xe`
