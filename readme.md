# CLONES FOR EVERYBODY

## Setup

This has been tested with Ubuntu 14.04 on a Digital Ocean server.

Run:
```bash
$ ./setup/setup.sh
```

Edit `/srv/ustwo/config.py` and then restart supervisor:
```bash
$ sudo service supervisor restart
```

If you're having issues:
* nginx logs: `/var/log/nginx/`
* supervisor logs: `/var/log/supervisor/`
* celery logs: `/var/log/celery/`
* application logs: `/var/log/ustwo.log`
