cPanel Exporter
=========

An Ansible role to install Prometheus cPanel Exporter on Linux servers.

Requirements
------------

None

Role Variables
--------------

- cpanel_exporter_port: Port for the node exporter to listen on

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cpanel_exporter_role, cpanel_exporter_port: 9100 }

License
-------

BSD

Author Information
------------------

Ahmed Shibani <sheipani@gmail.com>