[![](https://github.com/ansible-roles-mamono210/mariadb_install/workflows/build/badge.svg)](https://github.com/ansible-roles-mamono210/mariadb_install/actions?query=workflow%3Abuild)

Role Description
=========

Install [MariaDB](https://mariadb.org) for CentOS7.

Requirements
------------

None

Role Variables
--------------

```YAML
---
# MariaDB root password
mariadb_root_password: password
```

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - mariadb_install
```

License
-------

BSD
