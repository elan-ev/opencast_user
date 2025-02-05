Ansible: Opencast User Role
===========================

![molecule](https://github.com/elan-ev/opencast_user/actions/workflows/molecule.yml/badge.svg)

This Ansible role creates an Opencast Linux user with a specific user and group
ID to ensure they are identical on the whole cluster.

Role Variables
--------------

- `opencast_user_name`
  - The username of the user to create
  - Defaults: `opencast`
- `opencast_user_group_name`
  - The group name of the user
  - Defaults: `opencast`
- `opencast_user_uid`
  - The user ID
  - Defaults: `7967`
- `opencast_user_gid`
  - The users group ID
  - Defaults: `7967`

Example Playbook
----------------

Example of how to use the role:

```yaml
- hosts: servers
  roles:
    - role: elan.opencast_user
```


License
-------

[BSD-3-Clause](LICENSE)

Author Information
------------------

[ELAN e.V](https://elan-ev.de/)