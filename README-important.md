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

    [mariadb]
    192.168.231.91 primary=db1 role=primary
    192.168.231.92 primary=db1 role=Nonprimary
    192.168.231.93 primary=db1 role=Noneprimary


Example Playbook
----------------

    - hosts:
        - "{{ Hosts }}
      roles:
        - cluster-standalone

License
-------

GPLv3

Author Information
------------------

Mark Mercado <davood.fazelly@gmail.com>

