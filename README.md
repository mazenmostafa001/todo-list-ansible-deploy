# Todo List Deployment using Ansible & Docker

This project deploys a Node.js Todo List application using:
- Docker
- Docker Compose
- Ansible
- Watchtower for auto updates

## Architecture
- EC2 (Ubuntu)
- Docker & Docker Compose
- MongoDB
- Node.js App

## How to Run

### 1. Update inventory
Set your EC2 public IP in the inventory file.

### 2. Run Ansible Playbook
```bash
ansible-playbook -i inventory playbook.yml

