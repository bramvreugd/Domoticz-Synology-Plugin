# Domoticz-Synology-Plugin
Synology Monitoring Plugin. 
<br>Collects CPU, Memory, Temperature, HDD Information and network load of Synology NAS Units

This plugin was based on the plugin by febalci

New version:<br>
2.0: Added network load of NAS. The bonded ethernet port 1 and 2 is used.<br>
<br>
If there is a need for monitoring ethernet port 1 as well I can add it, just ask.<br>


Installation:<br>
On Synology: Open Control Panel - Terminal & SNMP - SNMP - Enable SNMP Service and SNMPv1,SNMPv2c service and note down Community password.<br>
On Domoticz install pysnmp: sudo pip3 install pysnmp<br>
Install plugin.py to Domoticz plugins Synology folder.<br>

Configuration in Domoticz:

Address: Synology IP Address<br>
Community: Synology SNMP Community Password<br>
DSM OID: Change this OID to 38 on DSM 5.1, 41 on DSM 6.0, 42 on DSM 6.1, 51 on DSM 6.2, 57 on DSM 7.2<br>
Check Interval: Poll interval in minutes
<br>
