[![Galaxy](https://img.shields.io/badge/galaxy-dockpack.base__goss-blue.svg?style=flat)](https://galaxy.ansible.com/dockpack/base_goss)[![Build Status](https://api.travis-ci.org/dockpack/base_goss.svg)](https://travis-ci.org/dockpack/base_goss)


An ansible-role to download the **goss** binary to a dir set by {{ goss_path }}

Requirements
------------

None

Role Variables
--------------

goss_version: Defaults to v0.3.4, which is latest at the time of writing. Any new versions need to be handjammed into vars/main.yml because of the manual checksum validation. Currently supports all known versions

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: sean-abbott.install-goss, goss_version: v0.2.5 }

License
-------

GPLv2

Author Information
------------------

Sean's a pretty great guy. I'm not sayin', I'm just sayin'.
bbaassssiiee uses Ansible a lot.
