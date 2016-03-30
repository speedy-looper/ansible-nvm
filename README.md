Role Name
=========

NVM installer
[![Build
Status](https://travis-ci.org/speedy-looper/ansible-nvm.svg?branch=master)](https://travis-ci.org/speedy-looper/ansible-nvm)

Requirements
------------

N/A

Role Variables
--------------

    ---
    nvm:
      user: deploy
      verson: master
      node_version: 0.12.9


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

Any contriubtion are welcome.
