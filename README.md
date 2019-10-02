Ansible Role: Node 10
=========

Ansible role to install Node version 10 on RHEL/CentOS

Requirements
------------

None.

Role Variables
--------------

The following variables must be set with values in the host_vars or group_vars:
```
node_modules_dirs
node_server_role_version
node_version
```

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: jhd3.ansible_role_node10 }

License
-------

MIT

Author Information
------------------

Create in 2019 by James Dugger for Cyberitas Technologies, LLC
