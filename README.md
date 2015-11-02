Role Name
=========

Baseline for satisfying developer environment for user: codey

Role Variables
--------------

| Variable        | Purpose                 |
|-----------------|-------------------------|
| codey_state     | Ansible state           |
| codey_groups    | Supplemental group csv  |


Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: coxley.codey, platform: workstation }

License
-------

WTFPL-2.0

Author Information
------------------

Codey Oxley <codey.a.oxley+os@gmail.com>
