# Ansible Playbooks

Ansible playbooks to update hosts and services.

Activate python virtual env: `source /ansible-run/bin/activate`

## Portainer playbook

Stop/Remove/Pull/Start of Portainer CE and Portainer Agent.

`ansible-playbook -i portainer-hosts.yml portainer-tasks.yml`

## Main Playbook

Runs apt-get to update all hosts and check if their respective service is up and running.

`ansible-playbook -i main-hosts.yml main-tasks.yml`
