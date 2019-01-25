#to prevent unnecessary email attempts, include
MAILTO=""

#to log cron activity to its own file
edit /etc/rsyslog.d/50-default.conf
Uncomment the "#cron." line
and then see your new /var/log/cron.log file


