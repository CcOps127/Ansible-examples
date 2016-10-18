Role Name
=========
Use ansible install Mariadb on Ubuntu 16.04 LTS 
 
Requirements
------------
 
 
Role Variables
--------------
defaults/main.yml 
 
Dependencies
------------
 
Example Playbook
----------------
    - hosts: mariadb
      remote_user: root
      gather_facts: True
      roles:
        - mariadb
 
Install: ansible-playbook -i hosts Squid --tags 'install'
Unstall: ansible-playbook -i hosts Squid --tags 'uninstall'
Service: ansible-playbook -i hosts Squid --tags 'service'
 
License
-------
BSD
 
Author Information
------------------
Name: Charlie.Cui
Email: charlie.cui127@gmail.com  
