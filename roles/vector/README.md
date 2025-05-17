Role Name
=========

Deploy [Vector](https://vector.dev/) tool using ansible.

Requirements
------------

* Ansible >= 2.17

* Python >= 3.10.12

* Jinja >= 3.0.3

(It might work on previous versions, but we cannot guarantee it)

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

| Scope    | Variable       | Default | Description                 |
|----------|----------------|---------|-----------------------------|
| defaults | vector_version | 0.46.1  | Vector distributive version |

Dependencies
------------

-

Example Playbook
----------------

```
    - name: Install Vector
      hosts: vector
      become: true
      roles:
        - vector
      tags: vector
```

License
-------

MIT

Author Information
------------------

Nataliya Khanova
