Ansible - apcupsd
=========

Manage acpupsd by Ansible

Requirements
------------

NA

Role Variables
--------------

All variables which can be overridden are stored in
[defaults/main.yml](defaults/main.yml) file with default values.

Dependencies
------------

- [community.general.apk](https://docs.ansible.com/ansible/latest/collections/community/general/apk_module.html)

Example Playbook
----------------

```yaml
    - hosts: servers
      roles:
         - { role: apcupsd, tags: [ apcupsd ] }
```

License
-------

GPLv3
