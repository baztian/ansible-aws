Aws ansible role
================

![CI](https://github.com/baztian/ansible-aws/workflows/CI/badge.svg)

Role to download, install and setup various tools for AWS (Amazon Web Services).

Example Playbook
----------------

    - hosts: servers
      become: yes
      roles:
         - role: baztian.aws

License
-------

MIT
