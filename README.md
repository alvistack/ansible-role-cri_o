# Ansible Role for CRI-O

[![Gitlab pipeline status](https://img.shields.io/gitlab/pipeline/alvistack/ansible-role-cri_o/master)](https://gitlab.com/alvistack/ansible-role-cri_o/-/pipelines)
[![GitHub release](https://img.shields.io/github/release/alvistack/ansible-role-cri_o.svg)](https://github.com/alvistack/ansible-role-cri_o/releases)
[![GitHub license](https://img.shields.io/github/license/alvistack/ansible-role-cri_o.svg)](https://github.com/alvistack/ansible-role-cri_o/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/galaxy-alvistack.cri_o-blue.svg)](https://galaxy.ansible.com/alvistack/cri_o)

Ansible Role for CRI-O Installation.

## Requirements

This role require Ansible 2.10 or higher.

This role was designed for:

  - Ubuntu 18.04, 20.04, 20.10
  - CentOS 7, 8 Stream
  - openSUSE Leap 15.2, Tumbleweed
  - Debian 10
  - Fedora 33
  - RHEL 7, 8

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

[ansible-galaxy-requirements.yml](ansible-galaxy-requirements.yml)

## Example Playbook

[molecule/default/converge.yml](molecule/default/converge.yml)

This role could simply deploy to `localhost` as below:

    molecule converge -s default

## License

  - Code released under [Apache License 2.0](LICENSE)
  - Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

## Author Information

  - Wong Hoi Sing Edison
      - <https://twitter.com/hswong3i>
      - <https://github.com/hswong3i>
