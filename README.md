Role Name
=========

A brief description of the role goes here.


Example Playbook
----------------
```yaml

- hosts: all
  roles:

   - role: "ankit4rh.docker"
     vars:
      - docker_compose_version: "1.24.1"
      - docker_users:
          - "ubuntu"
          - "root"


License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
