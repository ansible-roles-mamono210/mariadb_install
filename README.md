[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/mariadb_install/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/mariadb_install/tree/main)

Role Description
=========

Install [MariaDB](https://mariadb.org) for CentOS7/Stream8.

Requirements
------------

None

Role Variables
--------------

```YAML
---
# MariaDB CentOS7 repository
mariadb_centos7_repo: http://yum.mariadb.org/10.7/centos7-amd64


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
