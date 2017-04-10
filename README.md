[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-typesafe-activator.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-typesafe-activator)
andrewrothstein.typesafe-activator
===========================

A role for installing [Lightbend's Activator](http://www.lightbend.com/community/core-tools/activator-and-sbt).

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
