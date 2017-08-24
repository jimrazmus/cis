# cis Ansible role

[![Build Status](https://travis-ci.org/jimrazmus/cis.svg?branch=master)](https://travis-ci.org/jimrazmus/cis)

Applies/verifies Center for Internet Security (CIS) recommendations/benchmarks to target server(s).

## Tested versions of Ansible, CIS, and OS

Ansible: 2.2.3.0, latest

Python: 2.7, 3.4

| OS | OS Version | CIS Specification Version |
| --- | --- | --- |
| Amazon Linux | 2017.03.0.20170401 | v2.0.0 - 06-02-2016 |
| CentOS | 7 | v2.1.1 - 01-31-2017 |
| Ubuntu | 16.04 LTS | v1.0.0 - 10-04-2016 |

## Requirements

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

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
