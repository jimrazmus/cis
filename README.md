# cis Ansible role

[![Build Status](https://travis-ci.org/jimrazmus/cis.svg?branch=master)](https://travis-ci.org/jimrazmus/cis)
[![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/jimrazmus/cis/blob/master/LICENSE)

Applies, or verifies, Center for Internet Security (CIS) benchmarks on target servers.

## Testing

Each combination of the following Ansible, Python, and Operating System versions are tested.

Ansible

* 2.2.3.0
* latest

Python

* 2.7
* 3.4

OS

* Amazon Linux 2017.03.0.20170401
* CentOS 7
* Ubuntu 16.04 LTS

## CIS Benchmark Versions

| OS | CIS Specification Version |
| --- | --- |
| Amazon Linux | v2.0.0 - 06-02-2016 |
| CentOS | v2.1.1 - 01-31-2017 |
| Ubuntu | v1.0.0 - 10-04-2016 |

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
