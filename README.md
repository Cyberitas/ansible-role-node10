Ansible Role: Node 10
=========

Ansible role to install Node version 10 on RHEL/CentOS

Requirements
------------

None.

Role Variables
--------------

From the default/main.yml
```
__node_modules_path: /srv/WebSite/node_modules
```
The following variable is required and passed into the playbook:
```$xslt
node_server_role_version
```
The directoruy location for the node_modules folder(s)
```
node_modules_dirs
```
Node version is passed into the role and playbook from user entery 
```$xslt
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
