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
    - role: docker
      docker_repo: "https://mirrors.aliyun.com/docker-ce"
      docker_registry_mirror: "https://registry.docker-cn.com"
      docker_dns:
        - 223.5.5.5
        - 223.6.6.6
        - 114.114.114.114
```

## License
The MIT License (MIT)
