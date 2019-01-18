# kubernetes

## Introduce
Use to install Kubernetes(kubelet, kubeadm, kubectl).

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
- name: Installing Kubernetes
  hosts: test
  become: yes
  
  roles:
    - kubernetes
```

## License
The MIT License (MIT)
