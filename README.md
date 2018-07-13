Ansible OpenVpn Role
=========

Installs openvpn simply as that.
Client certificates will be stored in /srv/client by default.

Use openvpn_conf.client list if you want to generate more than one client package.

Requirements
========
You will need to add to your ansible.cfg
```
hash_behaviour = merge
```
Because this role stores variables in arrays and you won't be able to change one variable without recreating full array.

TODO
======

* iptables rules creation.
* auto client package creation. with certificate added to config.
