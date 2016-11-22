consul-backinator
=========

[![Build Status](https://travis-ci.org/kostyrevaa/ansible-role-consul-backinator.svg?branch=master)](https://travis-ci.org/kostyrevaa/ansible-role-consul-backinator)

Installs and configures [consul-backinator](https://github.com/myENA/consul-backinator)

Requirements
------------

This role requires Ansible 2.1 or higher.

Role Variables
--------------

| Name                        | Description                      |
|-----------------------------|----------------------------------|
| backinator_version          | Version to download              |
| backinator_pkg              | Binary name                      |
| backinator_pkg_url          | Full url to download binary from |
| backinator_bin_dir          | Path to extract binary to        |

Dependencies
------------

None

Example Playbook
----------------

Install consul-backinator binary to /usr/local/bin

```
- hosts: all
  roles:
    - { role: kostyrevaa.consul-backinator }
```

License
-------

BSD

Author Information
------------------

Aleksandr Kostyrev
