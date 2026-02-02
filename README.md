# Domoticz-Synology-Plugin
Synology Monitoring Plugin.  Collects CPU, Memory, Heat, HDD Information and network load from Synology NAS Units

This plugin was based on the plugin by febalci

New version:
Added network load of NAS. The bonded ethernet port 1 and 2 is used.
If there is a need for monitoring ethernet port 1 as well I can add it, just ask.


Installation:
pysnmp Python3 module should be installed first
pip3 install pysnmp


Configuration:
Please Change DSM OID '51' to 38 on DSM 5.1, 41 on DSM 6.0, 42 on DSM 6.1, 51 on DSM 6.2, 57 on DSM 7.2
    
