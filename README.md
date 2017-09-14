# kubernetes_bare_metal_deployer
Kubernetes_bare_metal_deployer is a solution to auto deploy a ready-cluster kuberenetes production environment based on containers technology using Ansible as a provisioning engine.<br/>
* Start by editing this file to specify your hosts:
```
/etc/ansible/hosts
```
```
[host]
ip_address ansible_ssh_user=username
```
* After cloning the project run:
```
ansible-playbook playMe.yml
```
* Ensure ssh public key access to your hosts
```
ssh-copy-id username@hostname
```
enjoy :D
