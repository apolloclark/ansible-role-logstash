# Ansible Role: logstash

[![Build Status](https://travis-ci.org/apolloclark/ansible-role-logstash.svg?branch=master)](https://travis-ci.org/apolloclark/ansible-role-logstash)

Ansible Role to install and configure Elastic Logstash for:
- Ubuntu 18.04 Bionic LTS
- Ubuntu 16.04 Xenial LTS
- Debian 10 Buster
- Debian 9 Stretch
- RHEL 8 UBI
- RHEL 7 UBI
- CentOS 7
- Amazon Linux 2

## Requirements

None.

## Role Variables

Default values are in `defaults/main.yml`. You can overload the variables by
creating a dictionary called "logstash", ex:

    logstash:
      version: 7.3.0

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - apolloclark.logstash

## License

MIT / BSD

## Author Information

This role was created in 2017 by [Apollo Clark](https://www.apolloclark.com/)
