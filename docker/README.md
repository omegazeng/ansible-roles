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
      docker_repo: "https://mirrors.tuna.tsinghua.edu.cn/docker-ce"
      docker_log_max_size: 100m
      docker_log_max_file: 10
```

## License

The MIT License (MIT)
