# ntpd

## Introduce
Install ntp, enable and start ntpd.

## Installation
None

## Dependencies
None

## Requirements
* Ansible version at least 2.6
* CentOS 7

## Example
```yaml
- name: Configuring ntpd
  hosts: test
  become: yes

  roles:
    - ntpd
```

## License
The MIT License (MIT)
