[![Build Status](https://travis-ci.com/Mireiawen/ansible-role-mosh.svg?branch=master)](https://travis-ci.com/Mireiawen/ansible-role-mosh) [![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-mireiawen.mosh-blueviolet)](https://galaxy.ansible.com/mireiawen/mosh)


# Mobile Shell

Installs the Mobile Shell package mosh. Should work on most distributions.

## Requirements

EPEL repository is needed on Red Hat and CentOS and based distributions. You can use for example [Ansible Role: EPEL Repository](https://galaxy.ansible.com/geerlingguy/repo-epel)

## Role Variables

If needed, the mosh package name can be changed by specifying the `mosh_package` variable. It defaults to `mosh`

## Dependencies

None.

## Example Playbook

```
- hosts: "servers"
  roles:
  - "mireiawen.mosh"
```

## License
MIT, see `LICENSE`
