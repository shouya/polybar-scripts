# Script: battery-cyberpower

A shell script that shows the battery status for CyberPower UPS devices.

This script is able to display power supply changes in real time.

It requires access to run `pwrstat` as root, so you may need to adjust your system to allow this (for example `sudo`).


## Dependencies

* `pwrstat` from CyberPower's website


## Module

```ini
[module/battery-cyberpower]
type = custom/script
exec = ~/polybar-scripts/battery-cyberpower.sh
tail = true
```
