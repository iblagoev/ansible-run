# How to activate python env

Activate python virtual env: `source /ansible-run/bin/activate`

## Main Playbook

Runs apt-get / zypper up to update all hosts and check if their respective services are up and running.

`ansible-playbook -i main-hosts.yml main-tasks.yml`
