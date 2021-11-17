# ansible-system_modules

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_modules-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_modules)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_modules.svg)](https://github.com/lotusnoir/ansible-system_modules/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_modules?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56111)](https://galaxy.ansible.com/lotusnoir/system_modules)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56111)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Add or remove kernel modules

## Requirements

none

## Role variables

See [variables](/default/main.yml) for more details.

## Examples

        ---
        - hosts: system_modules
          become: yes
          become_method: sudo
          gather_facts: yes
          roles:
            - role: ansible-system_modules

## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

