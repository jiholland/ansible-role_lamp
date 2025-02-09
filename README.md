jiholland.lamp
==============

Provision Apache, MariaDB and PHP with SSL redirect, SELinux and firewalld enabled.

Requirements
------------

- [Ansible Posix Collection](https://galaxy.ansible.com/ui/repo/published/ansible/posix)

Role Variables
--------------

- lamp_selinux_state
- lamp_packages
- lamp_services
- lamp_fqdn
- lamp_mariadb_root_password
- lamp_mariadb_buffer_pool_size
- lamp_php_timezone

Dependencies
------------

None.

Example Playbook
----------------
```yaml
---
- name: Install Apache, MariaDB and PHP.
  hosts: "{{ target }}"
  roles:
    - jiholland.lamp
```
License
-------

BSD

Author Information
------------------

Jørn Ivar Holland
