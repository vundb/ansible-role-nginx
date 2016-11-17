Ansible Role Nginx
======================================

Ansible role to installing and configuring nginx on gentoo instances.

Requirements
------------

None.

Role Variables
--------------

- `nginx_user`:
Name of system user to run service with. Default value is "nginx"

- `nginx_group`:
Name of system group to run service with. Default value is "nginx"

- `nginx_services`:
Array with services to be restarted on configuration changes. Default value
is ["nginx"]

Dependencies
------------

None.

Example Playbook
----------------
```
- hosts: all
  roles:
    - role: vundb-nginx
```

License
-------

MIT

Author Information
------------------

- You can find more roles in my GitHub channel [vundb](https://github.com/vundb)
- Follow me on Twitter [@vundb](https://twitter.com/vundb)
