andrewrothstein.typesafe-activator
===========================
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-typesafe-activator.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-typesafe-activator)

Installs [Lightbend's Activator](http://www.lightbend.com/community/core-tools/activator-and-sbt).

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
    - andrewrothstein.typesafe-activator
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
