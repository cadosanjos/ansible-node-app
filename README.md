Role Name
=========

This role installs the pre-req for ansible, docker, prometheus and grafana. The purpose is run a node app and monitor it.

Requirements
------------

Ubuntu

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: "{{ host }}"
      gather_facts: false
      roles:
         - ansible-node-app

License
-------

MIT


Author Information
------------------

Camilla dos Anjos Daniel
