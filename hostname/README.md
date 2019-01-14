# hostname

## Introduce
Use to set hostname, and generate /etc/hosts.

**Warning**: This playbook will change hostname, and cover /etc/hosts.

## Installation
None

## Dependencies
None

## Requirements
Ansible version at least 2.6

## Example
```yaml
- name: Setting hostname, and generating /etc/hosts.
  hosts: test
  become: yes
  
  roles:
    - { role: hostname,  hostname_prefix: "test-" }
```

## License
The MIT License (MIT)
