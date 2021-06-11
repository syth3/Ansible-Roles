Role Name
=========

Install Python from source on a Debian-based linux system.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):
```
python_version: 3.9.0
python_from_source_url: https://www.python.org/ftp/python/{{ python_version }}/Python-{{ python_version }}.tar.xz
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: ubuntu-machines
      become: yes
      roles:
         - install-python-from-source

License
-------

MIT/BSD

Author Information
------------------

This role was created in 2021 by Jake Brown
