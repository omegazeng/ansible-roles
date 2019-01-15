# docker

## Introduce
Use to install Docker CE.

## Installation
None

## Dependencies
None

## Requirements
* Ansible version at least 2.6
* Ubuntu 16/18
* CentOS 7

## Example
```yaml
- name: Installing Docker CE
  hosts: test
  become: yes

  roles:
    - docker
```

## License
The MIT License (MIT)
