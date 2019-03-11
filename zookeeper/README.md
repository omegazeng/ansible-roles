# zookeeper

## Introduce
Use to install zookeeper, and set up a cluster.

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
10.0.0.1 node_id=1
10.0.0.2 node_id=2
10.0.0.3 node_id=3
```

```yaml
- name: Installing Zookeeper
  hosts: test
  become: yes

  roles:
    - role: zookeeper
      memory_percent: 0.4
```

## License
The MIT License (MIT)
