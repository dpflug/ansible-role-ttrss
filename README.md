TT-RSS
======

[![Build Status](https://travis-ci.org/MicroJoe/ansible-role-ttrss.svg?branch=master)](https://travis-ci.org/MicroJoe/ansible-role-ttrss)

TinyTinyRSS role for nginx with letsencrypt support.

Requirements
------------

- LetsEncrypt
- Postgresql
- Nginx
- Debian Stretch

Role Variables
--------------

TBD

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: MicroJoe.ttrss
          nginx_server_name: tt-rss.example.com
          letsencrypt_activate: true
          letsencrypt_https: true
          tags: [ttrss]

License
-------

MIT

Author Information
------------------

Romain Porte
