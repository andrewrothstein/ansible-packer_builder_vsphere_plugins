andrewrothstein.packer_builder_vsphere_plugins
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-packer_builder_vsphere_plugins.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-packer_builder_vsphere_plugins)

Installs JetBrains [packer-builder-vsphere](https://github.com/jetbrains-infra/packer-builder-vsphere) plugins.

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
    - andrewrothstein.packer_builder_vsphere_plugins
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
