# Ansible Role - Linux Server Base Configuration

[![Build Status](https://travis-ci.org/elnebuloso/ansible-role-server-base.svg?branch=master)](https://travis-ci.org/elnebuloso/ansible-role-server-base)

Setup a Linux Server.

## Requirements

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```
# config for updating packages on provisioning
# values can be: dist, full, safe
server_base_apt_upgrade: ""

# the locales to generate
server_base_locales:
  - de_DE
  - de_DE@euro
  - de_DE.UTF-8
```

## Example Playbook

```
- hosts: localhost
  vars:
    server_base_apt_upgrade: "dist"
    server_base_locales:
      - de_DE
      - de_DE@euro
      - de_DE.UTF-8
  roles:
    - { role: elnebuloso.server-base }
```

## Dependencies

None.

##  License

MIT

##  Author Information

This role was created in 2016 by [elnebuloso](https://github.com/elnebuloso/)