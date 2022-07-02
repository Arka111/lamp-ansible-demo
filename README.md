# LAMP Deployment via Ansible

Automated deployment of a LAMP server via Ansible.

* Linux
  * Ubuntu 20.04
  * CentOS 8 (To be supported)
* Apache Web Server
* MySQL
  * MySQL
  * MariaDB
* Php 7

## Guide

```bash
git clone https://github.com/Arka111/lamp-ansible.git
ansible-playbook run_playbook.yml
```

## Design

This is an Ansible playbook with different roles

Roles

* Install Apache2
* Configure Apache2
* Install Mysql
* Configure Mysql
* Install Php7
* Configure Php7
