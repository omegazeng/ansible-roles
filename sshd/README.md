# sshd

**Warning**: This role will set PasswordAuthentication to no.
## Introduce
Use to configure sshd.

## Installation
None

## Dependencies
None

## Requirements
* Ansible version at least 2.0
* Ubuntu 16 / CentOS 7

## Example
```yaml
- name: Configuring sshd
  hosts: test
  become: yes

  roles:
    - sshd
```

## License
The MIT License (MIT)

See the [LICENSE](LICENSE) file for details.
