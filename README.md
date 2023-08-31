# Ansible Role: firewall

[![Lint](https://github.com/dcjulian29/ansible-role-firewall/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-firewall/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-firewall.svg)](https://github.com/dcjulian29/ansible-role-firewall/issues)

This an Ansible role to configure the firewall settings using iptables.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.firewall
  src: https://github.com/dcjulian29/ansible-role-firewall.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
