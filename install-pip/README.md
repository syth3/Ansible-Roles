Role Name
=========

Install pip on a linux system.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):
```
# Python executable to use when installing pip
python_executable: /usr/bin/python3
```

Dependencies
------------

None.

Example Playbook
----------------

```
- hosts: ubuntu-workstations
  roles:
      - install-pip
```

License
-------

MIT/BSD

Author Information
------------------

This role was created in 2021 by Jake Brown
