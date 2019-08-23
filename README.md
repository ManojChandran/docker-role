Role Name
=========

Role will help install docker, both Debian ans RedHat.

Requirements
------------

NA

Role Variables
--------------

NA

Dependencies
------------

NA

Playbook
----------------
Sample play book to run the docker_role.

```
---
- hosts: all  
  become: true
  roles:
  - role: manojchandran.docker_role
```
```
use command:
ansible-playbook myplaybook.yaml -K
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
