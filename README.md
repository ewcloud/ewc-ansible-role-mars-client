EWC Ansible Role Mars Client
============================

Install MARS Client on the EWC.

Requirements
------------
None

Role Variables
--------------
 - `repo_base`: Repository where to find the mars-client packages. Default: https://nexus.ecmwf.int
 - `repo_suffix`: Choose wether to use 'stable', 'staging' or 'bleeding-edge'. Default: stable

Example Playbook
----------------

    - hosts: all
      roles:
         -  ewc-ansible-role-mars-client

License
-------

Apache 2.0.

Author Information
------------------

ECMWF for the European Weather Cloud