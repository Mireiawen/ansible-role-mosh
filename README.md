# Mobile Shell

Installs the Mobile Shell package mosh. Should work on most distributions.

## Requirements

EPEL repository is needed on Red Hat and CentOS and based distributions. You can use for example (https://galaxy.ansible.com/geerlingguy/repo-epel](Ansible Role: EPEL Repository)

## Role Variables

If needed, the mosh package name can be changed by specifying the `mosh_package` variable. It defaults to `mosh`

## Dependencies

None.

## Example Playbook

    - hosts: "servers"
      roles:
         - "mireiawen.mosh"

## License
MIT, see `LICENSE`
