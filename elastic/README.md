# elastic

## Introduce

Use to install ELK, and set up a cluster.

## Installation

None

## Dependencies

openjdk

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
- name: Installing ELK
  hosts: test
  become: yes

  roles:
    - role: elastic
      es_memory_percent: 60
      ls_memory_percent: 20
```

## License

The MIT License (MIT)
