joenyland.ssh
=========================

[![CI](https://github.com/JoeNyland/ansible-ssh-role/actions/workflows/ci.yml/badge.svg)](https://github.com/JoeNyland/ansible-ssh-role/actions/workflows/ci.yml)

Configures SSH.

Requirements
------------

None.

Role Variables
--------------

### `ssh_authorized_keys`

An array of authorised key maps.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: server
  roles:
    - role: ssh
      vars:
        ssh_authorized_keys:
          - user: jane
            key: https://github.com/janedoe.keys
```

License
-------

MIT

Author Information
------------------

⌨️ with ❤️ by [Joe Nyland](https://joe.nyland.io)
