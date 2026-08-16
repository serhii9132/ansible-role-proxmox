ansible-role-proxmox
=========

Install Proxmox VE on Debian 13 Trixie

Requirements
------------

This role requires Ansible 2.19 or higher

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  gather_facts: true
  roles:
    - serhii9132.ansible-role-proxmox
```

License
-------

MIT