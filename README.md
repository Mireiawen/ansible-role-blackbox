![Build Status](https://img.shields.io/gitlab/pipeline-status/mireiawenrose/ansible-roles/blackbox?branch=master&style=plastic) [![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-mireiawen.blackbox-blueviolet?style=plastic)](https://galaxy.ansible.com/mireiawen/blackbox)

# BlackBox
Installs the [Stack Exchange BlackBox](https://github.com/StackExchange/blackbox) security utility. Should work on most distributions.

## Requirements
Installation requires the utilities `make` and `find` to be available.

## Role Variables
You can specify which version to install by specifying the version wanted in the `blackbox_version`. It defaults to `stable` version.

If needed, the reinstall can be forced by setting the `blackbox_force_build` to true.

## Dependencies
None.

## Example Playbook
    - hosts: "servers"
      roles:
         - "mireiawen.blackbox"

## License
MIT, see `LICENSE`
