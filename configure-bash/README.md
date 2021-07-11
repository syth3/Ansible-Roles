Role Name
=========

Configure bash.

Requirements
------------

None

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):
```
bash_user: user
# There is no default value for bash_aliases. See the example playbook for how to use it
bash_aliases:
install_bashrc: no
```

Dependencies
------------

None.

Example Playbook
----------------

```
- hosts: linux-hosts
  vars:
    bash_user: ansible
    bash_aliases:
      - { alias: 'll', command: 'ls -l' }
      - { alias: 'la', command: 'ls -A' }
  roles:
    - configure-bash
```

License
-------

MIT/BSD

Author Information
------------------

This role was created in 2021 by Jake Brown
