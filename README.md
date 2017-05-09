OU Libraries Zabbix Agent
=========

Rudimentary Zabbix Agent Role installs Zabbix 3.0 Agent with sender and get functionality.
See the [Zabbix 3.0 Agent documentation](https://www.zabbix.com/documentation/3.0/manual/config/items/itemtypes/zabbix_agent).

Requirements
------------

Expects CentOS 7 and a Zabbix Server to communicate with via cleartext.

Role Variables
--------------

The following variables are defined:


```
# Sets ServerActive in zabbix_agentd.conf
zabbix_server_host:

```


Dependencies
------------


Example Playbook
----------------


License
-------

[MIT](https://github.com/OULibraries/ansible-role-zabbix-agent/blob/master/LICENSE)

Author Information
------------------

Jason Sherman
