memoryleak.mysql
=========

Installs mysql from official repositories.

Requirements
------------

None

Role Variables
--------------
```
mysql_server_packages:
  - mysql-community-server

mysql_client_packages:
  - mysql-community-client
```

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: memoryleak.mysql }

License
-------

BSD

Author Information
------------------

Haydar Ciftci <haydar.ciftci@gmail.com>
