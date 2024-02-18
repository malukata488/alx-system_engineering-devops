0x13. Firewall
0x13-firewall

in the advanced task
1)sudo vim /etc/ufw/sysctl.conf
2) remove commit from forward code (forward =1)
3)update -> sudo sysctl -p
4) sudo ufw allow 8080/tcp
5)sudo vim /rtc/ufw/before.rules
6) make it like in file 100
7) disable and enable ufw


