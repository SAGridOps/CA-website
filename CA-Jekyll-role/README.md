[![Build Status](https://travis-ci.org/SAGridOps/CA-website.svg)](https://travis-ci.org/SAGridOps/CA-website)
NICIS CA Website
=========

This is a role for a jekyll-based website for a certificate authority

Requirements
------------

Uses the Ansible modules :

  * gem
  * yum
  * get_url

Requires a compiler and unzip on the remote side

Role Variables
--------------

The role has variables for the base dependencies and the ruby installation.

Dependencies
------------

There are no dependencies.

Example Playbook
----------------

You can apply the role using the default variables.

    - hosts: servers
      roles:
         - { role: brucellino.CA-Jekyll-Role }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
