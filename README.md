create terraform user
=========

Role for creating a user for executing terraform

Requirements
------------

Only tested with the condition below:
- CentOS7 and RHEL7
- Ansible 2.8


Role Variables
--------------
None

Dependencies
------------

Role terraform should be called after calling this role

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: create-terraform-user }

License
-------

BSD

Author Information
------------------

nm7-jp
