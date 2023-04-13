# containerd

## Introduce

Use to install Containerd.

## Installation

None

## Dependencies

None

## Requirements

* Ansible version at least 2.6
* Ubuntu 20
* CentOS 7

## Example

```yaml
- name: Installing Containerd
  hosts: test
  become: yes

  roles:
    - role: containerd
```

## License

The MIT License (MIT)
