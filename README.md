# zbx-win-agent-ping
Zabbix v4.4 template for ICMP ping from Zabbix windows agent without any external scripts or user parameters.
Just put the comma-separated target list in user macro {$PING_LIST} at the template or host level and run the "get icmp ping list" item.
