software_ansible
=========

This role will install software_ansible software

Requirements
------------

All dependencies will appear on requirements.yml file

Role Variables
--------------

software_packages:
  - ansible

repo_url: 'ppa:ansible/ansible'


Not defined yet. But in the future we could stage software version in here

Dependencies
------------

All dependencies will appear on requirements.yml file

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: xussof.software_ansible }

License
-------

BSD

Author Information
------------------
Made by @xussof
