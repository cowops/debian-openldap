Debian-OpenLDAP
===========

 OpenLDAP Software is an open source implementation of the Lightweight Directory Access Protocol.

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-openldap }

Tasks
-----

  - Install [openldap](http://www.openldap.org/)


License
-------

BSD
