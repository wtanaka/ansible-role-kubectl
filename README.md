[![Build Status](https://travis-ci.org/wtanaka/ansible-role-kubectl.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-kubectl)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-kubectl.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-kubectl)

wtanaka.kubectl
===============

Installs kubectl command line program that controls the Kubernetes
cluster manager.

Example Playbook
----------------

    - hosts: servers
      roles:
         - wtanaka.kubectl

### `kubectl_should_shortcircuit`

Default: True

when True, the role short-circuits itself if kubectl is already installed

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)

License
-------

GPLv2

Author Information
------------------

https://wtanaka.com/
