Ansible role: bootstrap
=========

[![Build Status](https://travis-ci.com/Provizanta/ansible-role-bootstrap.svg?branch=master)](https://travis-ci.com/Provizanta/ansible-role-bootstrap)

Bootstrap a clean machine to install Python3 for use with Ansible.

Role significantly inspired by:
  - https://github.com/rembik/ansible-role-bootstrap

Requirements
------------

None

Role Variables
--------------

These defaults are set in defaults/main.yml:

    bootstrap_user: root

Dependencies
------------

None

Example Playbook
----------------

    - hosts: server
      gather_facts: false
      become: false
      roles:
        - bootstrap

License
-------

MIT

Author Information
------------------

Tibor Csóka
