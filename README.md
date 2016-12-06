## Install Ansible
Go here: http://docs.ansible.com/ansible/intro_installation.html

And install Ansible on your machine

## Configure hosts
Edit hosts file in root directory

The server names should be under a group named zkHosts and kafHosts

## Run software
Run ansible-playbook -i hosts site.yml -kK and input your password
