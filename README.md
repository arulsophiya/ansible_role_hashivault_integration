# ansible_role_hashivault_integration
Ansible role to manage secrets in Hashicorp Vault.

#### To include the role in playbooks

```
- name: Test role
  hosts: all
  gather_facts: false
  roles:
   - ansible_role_hashivault_integration
```