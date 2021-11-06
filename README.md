# YOU.opensearch
[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT)

## Description

Role Variables
--------------

See `defaults/main.yml` and `vars/main.yml`, or the example below

Dependencies
------------

See `meta/main.yml` for other roles dependencies

Example Playbook
----------------

```yaml
---
- hosts: all
- roles:
  - role: opensearch
    vars:
      your_role_variable_here: true
      your_role_variable_list_also_here:
        - one
        - 2
        - b'11'
```

## Authors

* **Pavel Klyuev**

## Acknowledgments

* [Ansible Linting](https://medium.com/faun/linting-your-ansible-playbooks-and-make-a-continuous-integration-ci-solution-bcf8b4ea4c03)
* [Molecule examples](https://github.com/ansible/molecule/tree/master/test/scenarios/driver)
* [Testinfra](https://github.com/philpep/testinfra)
