Keep to nothing special.

wirecutter

ubuntu
github/gitlab
golang
vim

snmp
statsd
prometheus
grafana

3 2 1 backups
backblaze
local disposables

historic config backups
log2rotate?

This will run golang cronjobs,
configured by one crontab,
they will read snmp and send statsd
they will store backups
they will rotate backups

services will be authenticated and authorized
using apache pointing to AD/x.509
12-factor app model will be followed

Docker may be examined for its contained clean service restarts
otherwise container madness should be discouraged.

data will be stored in a suitable ansible dynamic inventory source
If needed, a sqlite file will support process coordination in the short-term

Never finish a day without updating tomorrow's todo list.
