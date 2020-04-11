![Ansible Lint](https://github.com/johanneskastl/ansible-role-add_screenrc/workflows/Ansible%20Lint/badge.svg)

add_screenrc
=========

Adds a .screenrc for root and (if configured) any unprivileged users

Requirements
------------

None.

Role Variables
--------------

`additional_users`: Name(s) of unprivileged users

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: johanneskastl.add_screenrc}

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
