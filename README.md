# ansible-apps_wazuh_manager

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_wazuh_manager-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_wazuh_manager)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_wazuh_manager.svg)](https://github.com/lotusnoir/ansible-apps_wazuh_manager/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_wazuh_manager?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_wazuh_manager)
![Ansible Quality Score](https://img.shields.io/ansible/quality/)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Install and configure wazuh manager to get security alerts on kibana

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_wazuh_manager
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_wazuh_manager


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

