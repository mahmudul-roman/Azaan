# Azaan

## Crontab File

XDG_RUNTIME_DIR=/run/user/1000
0 1 * * * /usr/bin/python3 /home/pi/azaan/azaan.py >> /tmp/cron_output.log 2>&1
