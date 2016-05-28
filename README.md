# Ansible Role - Linux Server Base Configuration

[![Build Status](https://travis-ci.org/elnebuloso/ansible-role-server-base.svg?branch=master)](https://travis-ci.org/elnebuloso/ansible-role-server-base)

Setup an Ubuntu Linux Server.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```
server_base_timezone: "Europe/Berlin"
```

the timezone the server is running

```
server_base_locales:
  - de_DE
  - de_DE@euro
  - de_DE.UTF-8
```

the locales to generate

## Example Playbook

```
- hosts: localhost
  vars:
    server_base_timezone: "Europe/Berlin"
    server_base_locales:
      - de_DE
      - de_DE@euro
      - de_DE.UTF-8
  roles:
    - { role: elnebuloso.server-base }
```

##  License

MIT

##  Author Information

This role was created in 2016 by [elnebuloso](https://github.com/elnebuloso/)