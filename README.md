# Ansible Role - Setup Server Essentials

[![Build Status](https://travis-ci.org/elnebuloso/ansible-role-server-base.svg?branch=master)](https://travis-ci.org/elnebuloso/ansible-role-server-base)

Setup Server Essentials

## Requirements

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Supported Distributions

- ubuntu14
- ubuntu16

## Role Variables

- [`vars/main.yml`](https://github.com/elnebuloso/ansible-role-server-base/blob/master/vars/main.yml)
- [`vars/ubuntu14.yml`](https://github.com/elnebuloso/ansible-role-server-base/blob/master/vars/ubuntu14.yml)
- [`vars/ubuntu16.yml`](https://github.com/elnebuloso/ansible-role-server-base/blob/master/vars/ubuntu16.yml)
- Variables prefixed with __ (2 Underscores) are Defaults, overwrite them by writing without the Underscores

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