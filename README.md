# Ansible Role: ZFS

[![Build Status](https://travis-ci.org/hwwilliams/ansible-role-zfs.svg?branch=master)](https://travis-ci.org/hwwilliams/ansible-role-zfs)

Installs and configures [ZFS On Linux](http://zfsonlinux.org/) on CentOS/Fedora/RedHat based Linux systems via an Ansible role.

Also on [Ansible Galaxy](https://galaxy.ansible.com/hwwilliams/zfs).

## Requirements

If installing ZFS with DKMS this role will also add the epel-release repo to install dependencies.

If installing ZFS with Kmods the epel-release repo isn't required.

## Role Variables

[defaults/main.yml](defaults/main.yml)

## License

MIT
