Get Hostname
=========

This module retrieves Hostname from a given server

Role Variables
--------------

```
  baseuri:
    required: true
    description:
      - iLO IP address of the server
    type: str
  username:
    required: true
    description:
      - Username of the server for authentication
    type: str
  password:
    required: true
    description:
      - Password of the server for authentication
    type: str
```

Dependencies
------------

No dependency on other modules.

Example Playbook
----------------

```
- hosts: servers
  roles:
    - get_hostname
```

License
-------

BSD

Author Information
------------------

T S Kushal (@TSKushal) Hewlett Packard Enterprise 2023 