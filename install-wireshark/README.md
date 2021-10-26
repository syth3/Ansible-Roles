Role Name
=========

Install Wireshark on a Debian-based linux system. This role will reboot the system after the installation.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):
```
wireshark_group_name: wireshark
# There is no default value for wireshark_group_users. See the example playbook for how to use it
wireshark_group_users:
```

Dependencies
------------

None.

Example Playbook
----------------

```
- hosts: ubuntu-workstations
  vars:
    wireshark_group_users:
      - ansible
      - ubuntu
  roles:
      - install-vscode
```

License
-------

MIT/BSD

Author Information
------------------

This role was created in 2021 by Jake Brown
