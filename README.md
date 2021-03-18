Aws ansible role
================

![CI](https://github.com/baztian/ansible-aws/workflows/CI/badge.svg)

Role to download, install and setup various tools for AWS (Amazon Web
Services). Requires `asdf` being install. Consider using
[baztian.asdf](https://github.com/baztian/ansible-asdf) to install
`asdf`.

Example Playbook
----------------

    - hosts: servers
      become: yes
      roles:
         - role: baztian.asdf
         - role: baztian.aws

License
-------

MIT
