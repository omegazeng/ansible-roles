# user

## Introduce
Use to manage users.

## Installation
None

## Dependencies
None

## Requirements
* Ansible version at least 2.0
* Ubuntu 12/14/16
* CentOS 6/7

## Example
```yaml
- name: Managing Users
  hosts: all
  become: yes
  
  roles:
    - { role: user,
        user_dict: {
          test1: "/bin/bash",
          test2: "/usr/sbin/nologin",
        }
      }
```

## License
The MIT License (MIT)

See the [LICENSE](LICENSE) file for details.
