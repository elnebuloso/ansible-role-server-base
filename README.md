# Ansible Role - Server Base Configuration

## Requirements

No special requirements; note that this role requires root access, so either run it in a playbook with a global `become: yes`, or invoke the role in your playbook like:

    - hosts: localhost
      roles:
        - role: elnebuloso.server-base
          become: yes
    
## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    server_base_timezone: "Europe/Berlin"

The Timezone use by the Server.

    server_base_locales:
      - de_DE
      - de_DE@euro
      - de_DE.UTF-8

The Locales to generate.

## Example Playbook

    - hosts: localhost
      vars:
        server_base_timezone: "Europe/Berlin"
        server_base_locales:
          - de_DE
          - de_DE@euro
          - de_DE.UTF-8
      roles:
        - { role: elnebuloso.server-base }

##  License

MIT

##  Author Information

This role was created in 2014 by [elnebuloso](https://github.com/elnebuloso/)