# ceph

## Introduce

Install ceph-common

## Installation

None

## Dependencies

None

## Requirements

Ansible version at least 2.6

## Example

```yaml
- name: Install ceph-common
  hosts: test
  become: yes
  
  roles:
    - role: ceph
      ceph_repo: "https://mirrors.tuna.tsinghua.edu.cn/ceph" # Default: "https://download.ceph.com"
```

## License

The MIT License (MIT)
