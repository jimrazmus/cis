# cis - Ansible Role

[![Build Status](https://travis-ci.org/jimrazmus/cis.svg?branch=master)](https://travis-ci.org/jimrazmus/cis)
[![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/jimrazmus/cis/blob/master/LICENSE)

Applies, or verifies, Center for Internet Security (CIS) benchmarks on target servers.

| OS | OS Version | CIS Specification Version |
| --- | --- | --- |
| Amazon Linux | 2017.03.0.20170401 | v2.0.0 - 06-02-2016 |
| CentOS | 7 | v2.1.1 - 01-31-2017 |
| Ubuntu | 16.04 | v1.0.0 - 10-04-2016 |

## Requirements

Ansible version 2.2.3.0 or higher

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Dependencies

None

## Example Playbook

    - hosts: servers
      roles:
         - { role: cis, x: 42 }

## License

MIT

## Author Information

Jim Razmus II
