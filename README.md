# Ansible Role: Samba (SMB)

[![Build Status](https://travis-ci.org/geerlingguy/ansible-role-samba.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-samba)

Installs Samba client and server for RHEL/CentOS.

## Requirements

Samba requires ports 137, 138, 139, 445 to be open to function properly. For easy firewall configuration, you can use the `geerlingguy.firewall` role.

## Role Variables

Available variables are listed below:

    samba_packages: []

A list of the Samba packages to install (OS-specific by default).

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - geerlingguy.samba

## License

MIT / BSD

## Author Information

This role was created in 2014 by [Jeff Geerling](https://www.jeffgeerling.com/), author of [Ansible for DevOps](https://www.ansiblefordevops.com/).
