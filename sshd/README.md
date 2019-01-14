# sshd

**Warning**: This role will set PasswordAuthentication to no by default.

## Introduce
Use to configure sshd.

## Installation
None

## Dependencies
None

## Requirements
* Ansible version at least 2.6
* Ubuntu 16 / CentOS 7

## Example
```yaml
- name: Configuring sshd
  hosts: test
  become: yes

  roles:
    - { role: sshd, ssh_PasswordAuthentication: "yes" }
```

## License
The MIT License (MIT)
