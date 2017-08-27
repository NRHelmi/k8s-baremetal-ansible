# kubernetes minimal setup using ansible

Run: ansible-playbook playMe.yml

## Specify your hosts under the: /etc/ansible/hosts

[host]
ip_address ansible_ssh_user=username

## Make sure you have ssh access to your hosts

ssh-copy-id username@hostname
