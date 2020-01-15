# zbx-win-agent-ping
Zabbix v4.4 template for ICMP ping test from the Zabbix Windows agent without any external scripts or user parameters.
Just put the comma-separated target list in user macro {$PING_LIST} at the template or host level and run the "get icmp ping list" item.
List example:
8.8.8.8,www.ya.ru,10.10.10.10
