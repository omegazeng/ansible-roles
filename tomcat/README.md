# tomcat

## Introduce
Use to install tomcat.

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
- name: Installing Tomcat
  hosts: test
  become: yes

  roles:
    - role: tomcat
      tomcat_memory_percent: 40
```

## License
The MIT License (MIT)
