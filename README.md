SQL Server install on Linux
=========

Installs SQL Server and sets the password to "sa_password" in your playbook. Not safe for use in production, as it relies on some unreliable hacks to get around the annoyingly interactive mssql-conf.py for setting up Microsoft SQL Server.

Requirements
------------

According to Microsoft SQL Server requires at least 3.25 GB RAM

Role Variables
--------------

- dbconfig

Dependencies
------------

None

Example Playbookz
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars:
        sa_password: testpassworD1
      roles:
         - { role: Norkart.mssql-server }

License
-------

MIT

Author Information
------------------

Kjartan Bjørset - Norkart AS 
