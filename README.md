# ansible-role-host-information #

[![GitHub Build Status](https://github.com/mcdonnnj/ansible-role-host-information/workflows/build/badge.svg)](https://github.com/mcdonnnj/ansible-role-host-information/actions)
[![CodeQL](https://github.com/mcdonnnj/ansible-role-host-information/workflows/CodeQL/badge.svg)](https://github.com/mcdonnnj/ansible-role-host-information/actions/workflows/codeql-analysis.yml)

A toy Ansible role to get information about a host.

## Requirements ##

None.

## Role Variables ##

None.

<!--
| Variable | Description | Default | Required |
|----------|-------------|---------|----------|
| optional_variable | Describe its purpose. | `default_value` | No |
| required_variable | Describe its purpose. | n/a | Yes |
-->

## Dependencies ##

None.

## Example Playbook ##

Here's how to use it in a playbook:

```yaml
- hosts: all
  become: true
  become_method: sudo
  tasks:
    - name: Display host information
      ansible.builtin.include_role:
        name: host_information
```

## Contributing ##

We welcome contributions!  Please see [`CONTRIBUTING.md`](CONTRIBUTING.md) for
details.

## License ##

This project is in the worldwide [public domain](LICENSE).

This project is in the public domain within the United States, and
copyright and related rights in the work worldwide are waived through
the [CC0 1.0 Universal public domain
dedication](https://creativecommons.org/publicdomain/zero/1.0/).

All contributions to this project will be released under the CC0
dedication. By submitting a pull request, you are agreeing to comply
with this waiver of copyright interest.

## Author Information ##

First Last - <first.last@gwe.cisa.dhs.gov>
