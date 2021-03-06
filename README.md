Ansible role: bootstrap
=========

![Build & Deploy](https://github.com/Provizanta/ansible-role-bootstrap/workflows/molecule/badge.svg?branch=master)

Bootstrap a clean machine to install Python3 for use with Ansible.

Optionally bootstrap also system with regard to distribution/technology normalization.

Role significantly inspired by:
  - https://github.com/rembik/ansible-role-bootstrap

Requirements
------------

None

Role Variables
--------------

These variables are defined in [defaults/main.yml](./defaults/main.yml):

    bootstrap_user: root

    bootstrap_system: true      # bootstrap and normalize systems, distributions...

Dependencies
------------

None

Example Playbook
----------------

    - name: Converge
      hosts: all
      gather_facts: false
      roles:
        - bootstrap

License
-------

MIT

Author Information
------------------

Tibor Csóka
