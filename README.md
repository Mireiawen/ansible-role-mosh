![Build Status](https://img.shields.io/gitlab/pipeline-status/mireiawenrose/ansible-roles/mosh?branch=master&style=plastic) [![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-mireiawen.mosh-blueviolet?style=plastic)](https://galaxy.ansible.com/mireiawen/mosh)

# Mobile Shell
Installs the Mobile Shell package mosh. Should work on most distributions.

## Requirements
None.

## Role Variables
 Configuration key       | Description                        | Default value
-------------------------|------------------------------------|----------------------
 `mosh_package`          | The name of the package to install | `mosh`
 `mosh_status`           | The desired status for the package | `latest`

## Dependencies
None.

## Example Playbook
```yaml
- hosts: "servers"
  roles:
  - "mireiawen.mosh"
```

## License
MIT, see `LICENSE`
