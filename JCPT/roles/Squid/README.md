Role Name
------------
Use ansible install squid on CentOS 7 OR Ubuntu 16.04 LTS

Requirements
------------


Role Variables
--------------
defaults/main.yml

vars/main.yml
  - RedHat.yml
  - Debian.yml

Dependencies
------------

Example Playbook
----------------
    - hosts: squid
      remote_user: root
      gather_facts: True
      roles:
        - Squid

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
