# Ansible Playbooks

Ansible playbooks to update hosts and services.

## Portainer playbook

Stop/Remove/Pull/Start of Portainer CE and Portainer Agent.
``` source /ansible-run/bin/activate```
``` ansible-playbook -i portainer-hosts.yml portainer-tasks.yml```

## Main Playbook

Runs apt-get to update all hosts and check if their respective service is up and running.

``` source /ansible-run/bin/activate```
``` ansible-playbook -i main-hosts.yml main-tasks.yml```
