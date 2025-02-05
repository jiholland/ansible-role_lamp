jiholland.lamp
==============

Install and configure Apache, MariaDB and PHP with basic security features enabled.

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
