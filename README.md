[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/mariadb_install/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/mariadb_install/tree/main)

Role Description
=========

Install [MariaDB](https://mariadb.org) for Linux.

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
