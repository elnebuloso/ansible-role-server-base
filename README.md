# Ansible Role - Linux Server Base Configuration

[![Build Status](https://travis-ci.org/elnebuloso/ansible-role-server-base.svg?branch=master)](https://travis-ci.org/elnebuloso/ansible-role-server-base)

Setup Essentials on an Ubuntu Server.

## Requirements

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Role Variables

- [`defaults/main.yml`](https://github.com/elnebuloso/ansible-role-server-base/blob/master/defaults/main.yml)
- [`vars/main.yml`](https://github.com/elnebuloso/ansible-role-server-base/blob/master/vars/main.yml)
- [`vars/ubuntu14.yml`](https://github.com/elnebuloso/ansible-role-server-base/blob/master/vars/ubuntu14.yml)
- [`vars/ubuntu16.yml`](https://github.com/elnebuloso/ansible-role-server-base/blob/master/vars/ubuntu16.yml)
- Variables prefixed with __ (2 Underscores) are Defaults, you can overwrite them using the Variable without the __ (2 Underscores)

## Example Playbook

```
- hosts: localhost
  roles:
    - role: elnebuloso.server-base
```

## Dependencies

None.

##  License

MIT

##  Author Information

This role was created in 2016 by [elnebuloso](https://github.com/elnebuloso/)