# zabbix-templates
My Zabbix templates.

*Some items are not working at the moment.*

## HP

## Microsoft Exchange

## Others
### Check extern http ip
Checks your external ip you have over http
If you need an Proxy, do it with "-x"
curl -x <ipofyourproxy>:<portofyourproxy> http://ipecho.net/plain; echo 2>&1

## Windows
### Windows basis
This templates checks a lot of things for you.
I added a discovery rule for partitions. You may have to expand or lower the RegEx:
^C|^D|^E|^F|^G|^H|^I
Only for C and D:
^C|^D

### Windows Domain Controller
Some items for initial DC services

### Windows Terminal Server
Checks the active, inactive, total sessions.