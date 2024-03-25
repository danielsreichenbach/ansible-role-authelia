# danielsreichenbach.authelia

[![CI][badge-img]][badge-url]
[![Galaxy Role][galaxy-img]][galaxy-url]

An Ansible role for installing and configuring [Authelia][] on Debian and
Ubuntu servers.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see
`defaults/main.yml`):

```yaml
```

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  roles:
    - danielsreichenbach.authelia
```

## License

MIT

## Author Information

This role has received contributions from

- [danielsreichenbach](https://github.com/danielsreichenbach)

[Authelia]: https://www.authelia.com/
[badge-img]: https://github.com/danielsreichenbach/ansible-role-authelia/workflows/CI/badge.svg?event=push
[badge-url]: https://github.com/danielsreichenbach/ansible-role-authelia/actions?query=workflow%3ACI
[galaxy-img]: https://img.shields.io/badge/ansible--galaxy-authelia-blue.svg
[galaxy-url]: https://galaxy.ansible.com/danielsreichenbach/authelia/
