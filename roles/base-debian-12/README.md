Role Name
=========

Basic setup role for Debian 12 servers


Example Playbook
----------------

A short example on how to call the role from a playbook

- name: Setup basic Debian 12 system
  hosts: targets
  become: true

  tasks:
    - name: Run the basic setup
      import_role:
        name: base-debian-12

License
-------

MIT