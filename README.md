# ansible-role-selinux
Ansible role to enable or disable SELinux on CentOS 7

[![Build Status](https://travis-ci.org/HauptJ/ansible-role-selinux.svg?branch=master)](https://travis-ci.org/HauptJ/ansible-role-selinux)

## Requirements
- Ansible 2.3+
- CentOS 7
- Extra Packages for Enterprise Linux (EPEL) repository
- Remi's RPM (REMI) repository

## Installation
1. Fork this repository
2. git submodule add <git host> roles/ansible-role-selinux
    - [submodule reference](https://chrisjean.com/git-submodules-adding-using-removing-and-updating/)

**Ansible Galaxy:** [HauptJ.selinux](https://galaxy.ansible.com/HauptJ/selinux/)


## Variables

### SELinux

| Name 						            | Default 							                    | Description 										   |
|-----------------------------|-------------------------------------------|------------------------------------|
| sel_disable                 | true                                      | true:disable SELinux; false: enable SELinux                    |
