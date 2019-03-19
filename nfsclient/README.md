# nfsclient

## Introduce

Use to install nfsclient.

## Installation

None

## Dependencies

None

## Requirements

* Ansible version at least 2.0
* Ubuntu 16.04/18.04
* CentOS 7

## Example

```ini
[test]
10.0.0.1
10.0.0.2
10.0.0.3
```

```yaml
- name: Installing nfsclient
  hosts: test
  become: yes

  roles:
    - nfsclient
```

## License

The MIT License (MIT)
