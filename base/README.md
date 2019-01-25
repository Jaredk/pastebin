Keep to nothing special.

ubuntu
github
golang
vim

snmp
prometheus
grafana
loki

3 2 1 backups (docean, rpi, usbkeys)
backblaze?
local disposables, swapped and shipped regularly.
one machine backs things up. (rpi)
Keep rotations in three places
Keep copies in all three up to date.
Log to local syslog (crontab time command 2>&1 | /usr/bin/logger -t "tag") 
a separate service will copy lines to remote server.


services will be authenticated and authorized
using apache pointing to AD/x.509
12-factor app model will be followed

Docker may be examined for its contained clean service restarts
otherwise container madness should be discouraged.

data will be stored in a suitable ansible dynamic inventory source
If needed, a sqlite file will support process coordination in the short-term

Never finish a day without updating tomorrow's todo list.
