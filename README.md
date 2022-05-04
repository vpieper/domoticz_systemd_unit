# Domoticz systemd unit
Systemd unit file for use with Domoticz, since it hasn't one (yet)

Builtin restart when not running (main reason I wanted this).

Instructions:

mv /etc/init.d/domoticz.sh /home/orangepi

vi /etc/systemd/system/domoticz.service

systemctl daemon-reload

systemctl enable -now domoticz.service
