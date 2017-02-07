# iptables/ip6tables systemd configuration 

Example of a persistent firewall based on systemd for Debian Jessie using fwbuilder.

### Install Steps
```sh
cp -r etc/systemd/system/iptables.service /etc/systemd/system/

systemctl daemon-reload

systemctl enable iptables.service

systemctl start iptables.service
```
