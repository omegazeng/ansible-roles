# kafka

## Introduce
Use to install Kafka, and set up a cluster.

## Installation
None

## Dependencies
zookeeper

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
- name: Installing Kafka
  hosts: test
  become: yes
  
  roles:
    - role: kafka
      zookeeper_memory_percent: 20
      kafka_memory_percent: 40
```

## License
The MIT License (MIT)
