Role Name
=========

A simple role to configure the fail2ban service on yum based machines.

Requirements
------------

epel-release package is required.

Role Variables
--------------

This role uses 3 variables:
log_path: /var/log/auth.log (The log path to store fail2ban logs.)
max_retry: 3 (After how many tries to ban the IP address.)
ban_time: -1 (Time in seconds the IP will be banned for. Use -1 for forever.)

Dependencies
------------

None

Example Playbook
----------------
    - name: execute fail2ban role
      hosts: servers
      roles:
         - fail2ban

License
-------

Free Use

Author Information
------------------

https://networknuts.net
