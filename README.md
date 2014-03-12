Ruby
========

Installs ruby (2.0 default) from brightbox repos

Requirements
------------

None

Role Variables
--------------

ruby_version: ruby2.0 - used in apt-get after brightbox repos are added

Dependencies
------------

None

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: defaults
      vars:
        - ruby_version: ruby2.0
      roles:
        - shadowkobolt.ruby

License
-------

BSD

Author Information
------------------

None
