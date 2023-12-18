# ansible
This repo contains various ansible playbooks

## Playbooks
### deploy_webapp.yml
This playbook deploys my webapp to a kubernetes cluster defined in `~/.kube/config`

## Developer Guide

This project uses poetry for dependencies along with ansible.

`poetry install`

`poetry run ansible-playbook playbook.yml`