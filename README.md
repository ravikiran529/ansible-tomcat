Role Name
=========

tomcat 

Description
===========

This role is to host multiple tomcat instances ( for dev/test ) in a single server with different ports.
Create your inventory with all your servers and make changes that fits best to your environment. 

Requirements
------------

A server with ansible installed and nexus artifact repository.

Example Playbook
----------------

    - hosts: localhost
      ansible_connection: local
      roles:
         - rolename

Author Information
------------------
Ravikiran Rapelli
DevOps Engineer
