Fuse
====
Install and configure fuse.

This role installs FUSE and configures `/etc/fuse.conf`. Only two options are available (see `fuse(8)` for additional details):
- `fuse_mount_max` sets the maximum number of FUSE mounts allowed to non-root users (defaults to 1000).
- `fuse_user_allow_other` allows non-root users to specify the `allow_other` and `allow_root` mount options (defaults to `no`).

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
Licensed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

Author Information
------------------
Luis Gracia <luis.gracia@ebi.ac.uk>
