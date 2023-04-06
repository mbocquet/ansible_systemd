# systemd

Ansible role to configure systemd.

## Requirements

None.

## Role Variables

See defaults/main.yml for details

## Dependencies

None.

## Install this role as submodule in a git repository

`git submodule add https://git.sekoya.org/mb/systemd.git roles/systemd`

## Example Playbook

    - hosts: servers
      roles:
        - systemd


    - hosts: servers
      roles:
        - role: systemd
          systemd_config:
            DefaultTimeoutStopSec: 10s
            DefaultOOMPolicy: stop

## License

GPLv3

## Author Information

http://www.sekoya.org
