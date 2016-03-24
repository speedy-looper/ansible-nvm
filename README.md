Role Name
=========

NVM installer

Requirements
------------

N/A

Role Variables
--------------

- node:
  - versions:
    - 0.12.9
  - default: 0

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: speedy-looper.nvm, become: yes }

License
-------

MIT

Author Information
------------------

Speed-of-light @ Speedy-looper :)
