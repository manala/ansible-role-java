# Ansible Role: Java [![Build Status](https://travis-ci.org/manala/ansible-role-java.svg?branch=master)](https://travis-ci.org/manala/ansible-role-java)

:exclamation: [Report issues](https://github.com/manala/ansible-roles/issues) and [send Pull Requests](https://github.com/manala/ansible-roles/pulls) in the [main Ansible Role repository](https://github.com/manala/ansible-roles) :exclamation:

This role will deal with the setup of __java__.

It's part of the [Manala Ansible stack](http://www.manala.io) but can be used as a stand alone component.

## Requirements

None.

## Dependencies

None.

## Installation

### Ansible 2+

Using ansible galaxy cli:

```bash
ansible-galaxy install manala.java
```

Using ansible galaxy requirements file:

```yaml
- src: manala.java
```

## Example playbook

```yaml
- hosts: servers
  roles:
    - { role: manala.java }
```

# Licence

MIT

# Author information

Manala [**(http://www.manala.io/)**](http://www.manala.io)
