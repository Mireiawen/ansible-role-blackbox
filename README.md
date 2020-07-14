[![Build Status](https://travis-ci.com/Mireiawen/ansible-role-blackbox.svg?branch=master)](https://travis-ci.com/Mireiawen/ansible-role-blackbox) [![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-mireiawen.blackbox-blueviolet)](https://galaxy.ansible.com/mireiawen/blackbox)


# BlacBbox
Installs the [Stack Exchange BlackBox](https://github.com/StackExchange/blackbox) security utility. Should work on most distributions.

## Requirements
Installation requires the utilities `git`, `make` and `find` to be available.

## Role Variables
You can specify which version to install by specifying the version wanted in the `blackbox_source_version`. It defaults to `HEAD` version.

If needed, the reinstall can be forced by setting the `blackbox_force_build` to true.

## Dependencies
None.

## Example Playbook
    - hosts: "servers"
      roles:
         - "mireiawen.blackbox"

## License
MIT, see `LICENSE`
