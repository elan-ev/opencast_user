Ansible: Opencast User Role
===========================

This Ansible role creates an Opencast Linux user with a specific user and group
id to ensure they are identical on the whole cluster.

Role Variables
--------------

Have a look at the [defaults](defaults/main.yml) to see variables you can configure.

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

BSD
