# sshd

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
    - role: sshd
      sshd_UseDNS: "no" # Default: "yes"
      sshd_PasswordAuthentication: "no" # Default: "yes"
```

## License
The MIT License (MIT)
