# common

## Introduce
Initial Server Setup

    install useful package
    disable firewalld
    disable selinux
    disable swap
    set timezone

## Installation
None

## Dependencies
None

## Requirements
Ansible version at least 2.6

## Example
```yaml
- name: Initial Server Setup
  hosts: test
  become: yes
  
  roles:
    - role: common
      timezone: "Asia/Shanghai" # Default: "UTC"
```

## License
The MIT License (MIT)
