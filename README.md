Fuse
====
Install and configure fuse utilities and libraries.

This role installs FUSE and configures `/etc/fuse.conf`.

Requirements
------------
See `meta/main.yml`.

Role Variables
--------------
See `defaults/main.yml`.

Dependencies
------------
None.

Example Playbook
----------------
Example:
```
- hosts: servers
  roles:
    - fuse
```

Licence
-------
Released under the [MIT license](https://opensource.org/licenses/MIT).

Author Information
------------------
Luis Gracia while at [EMBL-EBI](http://www.ebi.ac.uk/):
- luis.gracia [at] ebi.ac.uk
- GitHub at [luisico](https://github.com/luisico)
- Galaxy at [luisico](https://galaxy.ansible.com/luisico)
