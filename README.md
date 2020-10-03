# ansible-terraform

Ansible role for installing terraform

## Role Variables

* **terraform_version**: (default: 0.13.4)
* **terraform_platform**: (default: linux_amd64)
* **terraform_bindir**: (default: /usr/bin)
* **terraform_srcdir**: (default: /usr/local/src)

## Dependencies

This role does not have any dependencies

## Example Playbook

Install terraform on all servers

```
---
- name: base
  hosts: all
  become: yes
  gather_facts: yes

  roles:
    - role: terraform
```

## License

Apache-2.0
