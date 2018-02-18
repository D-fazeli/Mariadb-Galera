mamercad.mariadb-galera
=======================

Stands up MariaDB 10.2.11 (and Galera) on RHEL/CentOS

Warnings
--------

None

Requirements
------------

None

Role Variables
--------------

See the example inventory below...

Dependencies
------------

None

Example Inventory ==> /etc/ansible/hosts
-----------------

    [dbs]
    db1 ansible_host=192.168.231.91
    db2 ansible_host=192.168.231.92
    db3 ansible_host=192.168.231.93
    
 Example Playbook
----------------

    - hosts:
        - "{{ Hosts }}
      roles:
        - cluster

License
-------

GPLv3

Author Information
------------------

David fazeli <davood.fazelly@gmail.com>

