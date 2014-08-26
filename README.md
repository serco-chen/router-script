### autoddvpn script for routers using wget mode

#### How-to
1. setup firewall commands in administration of DD-WRT web interface
```
cd /tmp;wget https://raw.githubusercontent.com/serco-chen/router-script/master/scripts/run.sh  && /bin/sh run.sh || touch failed
```
2. configure dnsmasq

**For whose who have crappy routers**
