Ansible-Role-WordPress
=========
This is a simple role which installs WordPress

Requirements
------------
None

Role Variables
--------------

Dependencies
------------
  - ikambarov.php
  - ikambarov.apache

Example Playbook
----------------
  roles:
    - role: apache-role
    - role: php-role
      vars:
        php_version: "70"
    - role: mysql-role
    - role: wordpress-role

License
-------
MIT

Author Information
------------------
Islam Kambarov

