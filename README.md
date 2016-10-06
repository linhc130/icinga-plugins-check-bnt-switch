# icinga-plugins-check-bnt-switch

This plugin checks BNT G8052 G8264 switches, including

- CPU with warning and critical value
- Fans (RPM)
- Temperature
- Power supply status
- Global Health (G8264)
- SNMP



Worked with icinga 1.8.

Should be work with icinga 1.x / nagios


**IMPORTANT**: 
## Requirements : python 3.x

Attentions for install python 3.x on CentOS 6.  Please do google how-to install python 3 on CentOS 6 and install python 3.x on separate dir other than OS default python dir to ensure 'yum' and other system scripts which based on python 2.6.x scripts.


Reference from [G8052/G8264 monitoring plugin](https://exchange.nagios.org/directory/Plugins/Hardware/Network-Gear/Others/G8052-2FG8264-monitoring-plugin/details)

by Stephen HC Lin
