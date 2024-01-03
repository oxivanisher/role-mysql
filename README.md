mysql
=========

This role configures mysql backup (and only the backup!) with help of [oxiscripts](https://github.com/oxivanisher/oxiscripts). You can use [role-oxiscripts](https://github.com/oxivanisher/role-oxiscripts) to install and setup the oxiscripts.

Requirements
------------

See the oxiscripts commant above.

Role Variables
--------------

None.

Example Playbook
----------------
```yaml
- name: Mysql
  hosts: mysql_server
  collections:
    - oxivanisher.linux_server
  roles:
    - role: oxivanisher.linux_server.mysql
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_server](https://github.com/oxivanisher/collection-linux_server) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_server).
