# Ansible-Bootstarpper

Clone down this directory, then run the following commands to install the software you want.

1. Clone the repo:
```
git clone <repo-name>
```

2. Run the playbooks of your choice. e.g. tools/docker
```
ansible-playbook -i inventory/hosts.ini playbooks/install-tools.yaml -l local
```

