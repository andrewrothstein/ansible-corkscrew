andrewrothstein.corkscrew
===========================
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-corkscrew.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-corkscrew)

Installs or builds [corkscrew](https://github.com/andrewrothstein/corkscrew) from sources.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.corkscrew
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
