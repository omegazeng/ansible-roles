# common

## Introduce
Initial Server Setup

## Installation
None

## Dependencies
None

## Requirements
Ansible version at least 2.4

## Example
```yaml
- name: Initial Server Setup
  hosts: test
  become: yes
  
  roles:
    - { role: common, timezone: "Asia/Shanghai" }
```

## License
The MIT License (MIT)

See the [LICENSE](LICENSE) file for details.
