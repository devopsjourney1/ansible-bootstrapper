# Ansible-Bootstarpper

Clone down this directory, then run the following commands to install the software you want.

## Pre-reqs
Ansible must be installed.

## Usage:


1. Clone the repo:
```
git clone https://github.com/devopsjourney1/ansible-bootstrapper
cd ansible-bootstrapper
```

2. Run the playbooks of your choice. e.g. tools/docker
```
ansible-playbook -i inventory/hosts.ini playbooks/install-tools.yaml -l local
ansible-playbook -i inventory/hosts.ini playbooks/install-docker.yaml -l local
```

