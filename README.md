# ansible-base

prepares a Vultr VPN for use with ansible.

## Usage

```yaml
---
- name: Install base
  hosts: myvps
  gather_facts: no # <-- required
  roles:
    - role: insanity54.base
```