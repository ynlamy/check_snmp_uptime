This plugin can check the uptime of a host using SNMP v1 queries.

check_snmp_uptime is written in Bash and is distributed under the GPLv2 license. This plugin have been created by Yoann LAMY.

Usage: ./check_snmp_uptime -H xxx.xxx.xxx.xxx -C public -w 50 -c 100

-H ADDRESS
Name or IP address of host (default: 127.0.0.1)
-C STRING
Community name for the host's SNMP agent (default: public)
-w INTEGER
Warning level for the the number of days (default: 0)
-c INTEGER
Critical level for the the number of days (default: 0)
-h
Print this help screen
-V
Print version and license information

This plugin uses the 'snmpget' command included with the NET-SNMP package.
This plugin support performance data output. 

Examples :

./check_snmp_uptime -H xxx.xxx.xxx.xxx -C public -w 50 -c 100

This nagios plugins comes with ABSOLUTELY NO WARRANTY.

You may redistribute copies of the plugins under the terms of the GNU General Public License v2.
