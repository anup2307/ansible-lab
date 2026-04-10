# Ansible AWS Infrastructure Lab

## What this project does
- Creates VPC, Subnet, Internet Gateway
- Launches EC2 instance
- Configures infrastructure using Ansible
- Deletes infrastructure cleanly

## Tech Stack
- Ansible
- AWS (EC2, VPC)
- Docker (local testing)

## How to run
```bash
ansible-playbook playbooks/create_network.yml
ansible-playbook playbooks/create_ec2.yml
