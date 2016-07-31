get-url-ubuntu
================

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-get-url-ubuntu.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-get-url-ubuntu)

Install the dependendencies for the get_url module on Ubuntu.

* libcurl3

https://galaxy.ansible.com/suzuki-shunsuke/get-url-ubuntu/

Requirements
------------

Nothing.

Role Variables
--------------

* get_url_nonroot: Whether the remote_user is root or not. This variable is set automatically, and is used to execute tasks with the become option.

Dependencies
------------

* [suzuki-shunsuke.apt module](https://galaxy.ansible.com/suzuki-shunsuke/apt/)

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - { role: suzuki-shunsuke.get-url-ubuntu }
```

License
-------

MIT
