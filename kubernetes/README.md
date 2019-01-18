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
    - role: kubernetes
      k8s_repo: "https://mirrors.aliyun.com/kubernetes" # Default: "https://packages.cloud.google.com"
```

## License
The MIT License (MIT)
