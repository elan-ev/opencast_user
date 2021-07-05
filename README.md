Ansible: Opencast User Role
===========================

This Ansible role creates an Opencast Linux user with a specific user and group
id to ensure they are identical on the whole cluster.


Example Playbook
----------------

Example of how to use the role:

```yaml
- hosts: servers
  roles:
    - role: lkiesow.opencast_user
```


License
-------

BSD
