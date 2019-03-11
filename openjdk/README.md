# openjdk

## Introduce
Use to install openjdk.

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
- name: Installing openjdk
  hosts: test
  become: yes

  roles:
    - openjdk
```

## License
The MIT License (MIT)
