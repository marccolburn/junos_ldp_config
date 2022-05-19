LDP Configuration
=========

Configure LDP for Junos.

Requirements
------------


Role Variables
--------------
ldp_interfaces: List of Dictionaries containing LDP interfaces and unit
* name: Name of physical interface, string
* unit: unit of interface, int

ldp_settings: Dictinary containing settings for LDP
* loopback_unit: unit of interface, int

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: junos_ldp_config }

License
-------

BSD

Author Information
------------------

Marc Colburn Juniper
