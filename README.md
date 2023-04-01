Ansible Role: expinfo
=========

Ansible Role to install [expinfo](https://github.com/mjasny/expinfo/tree/daemon).

Requirements
------------

None

Role Variables
--------------

The variables defined in `defaults/main.yml` file describe the base URL for the repo and the download directory.

The entries in `vars/main.yml` can be used to change version that will be installed

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: adrianlut.expinfo }

License
-------

Apache 2.0
