ethical-sensors
---------------

The files needed for a sensor. Place them as indicated by the directory structure.
Then:
* Set the `auth_token` config option in `capture_packets`
* Install the aircrack-ng suite
* Create `/monitor.txt` at the root, containing the MAC for the wireless monitor card
* `systemctl enable monitor-config.service`
* `systemctl enable capture-packets.service`
* Reboot

