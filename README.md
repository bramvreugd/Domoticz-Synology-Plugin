# Domoticz-Synology-Plugin
Synology Monitoring Plugin.  Collects CPU, Memory, Heat, HDD Information and network load from Synology NAS Units

This plugin was based on the plugin by febalci

New version:
Added network load of NAS. The bonded ethernet port 1 and 2 is used.<br>
If there is a need for monitoring ethernet port 1 as well I can add it, just ask.


Installation:
On Synology: Open Control Panel - Terminal & SNMP - SNMP - Enable SNMP Service and SNMPv1,SNMPv2c service and note down Community password.
On Domoticz install pysnmp: sudo pip3 install pysnmp
Install plugin.py to Domoticz plugins Synology folder.

Configuration:

Address: Synology IP Address
Community: Synology SNMP Community Password
DSM OID: Change this OID to 38 on DSM 5.1, 41 on DSM 6.0, 42 on DSM 6.1, 51 on DSM 6.2, 57 on DSM 7.2
Check Interval: Poll interval in minutes

