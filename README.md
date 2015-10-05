[![Build Status](https://travis-ci.org/boeve-web-development/ansible-role-zend-server.svg?branch=master)](https://travis-ci.org/boeve-web-development/ansible-role-zend-server)[![Build Status](https://travis-ci.org/boeve-web-development/ansible-role-zend-server.svg?branch=develop)](https://travis-ci.org/boeve-web-development/ansible-role-zend-server)

# Zend Server

This role manages the installation of Zend Server with an Apache or Nginx web server.

For now we only support servers running Ubuntu (>= 14.04), when you prefer others operating systems, you can open a pull request or open an issue.

## Requirements

A server with an minimal install of Ubuntu server 14.04 and up.

## Role Variables

- zs_web_server: nginx or apache, the default web server is nginx.
- zs_php_version: 5.6 or 5.5, the default php version is 5.6.

## Example Playbook

An example of how to use this role (also take a look at tests/test.yml):

    - hosts: servers
      roles:
         - ansible-role-zend-server

## License

Included license file.
