Ansible role for python3-pip
==================================

Installs pip3 module

[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-pip3/workflows/Molecule%20Test/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-pip3/actions?query=workflow%3A%22Molecule+Test%22)
[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-pip3/workflows/Release/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-pip3/actions?query=workflow%3A%22Release%22)

Requirements
------------

Python3 must be installed in order for this role to work

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: ansible-role-pip3
```

License
-------

[Apache License](LICENSE)
