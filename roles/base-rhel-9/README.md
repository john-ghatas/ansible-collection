Role Name
=========

A basic playbook to install the packages most used in servers, this can be used as a starting point and extended with other roles to install specialized software.

Example Playbook
----------------

A basic playbook to call this role, also provided in the project.

- name: Setup basic RHEL 9 system
  hosts: targets
  become: true

  tasks:
    - name: Run the basic setup
      import_role:
        name: base-rhel-9

License
-------

MIT