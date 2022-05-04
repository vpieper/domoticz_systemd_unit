# domoticz_systemd_unit
Systemd unit file for use with Domotics

Restart when not running.

Instructions:
mv /etc/init.d/domoticz.sh /home/orangepi
vi /etc/systemd/system/domoticz.service
systemctl daemon-reload
systemctl enable -now domoticz.service
