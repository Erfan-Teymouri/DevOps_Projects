# VMware VM Provisioning Automation using Ansible

Enterprise automation project for provisioning and configuring VMware virtual machines.

## Features

- Cross-vCenter VM cloning
- Automatic VM power-on
- IP configuration
- Hostname configuration
- Oracle Linux deployment
- Multi-VM provisioning
- Infrastructure automation with Ansible

## Technologies

- Ansible
- VMware vSphere
- community.vmware Collection
- Linux
- SSH

## Workflow

Template Clone
↓
Power On
↓
Network Configuration
↓
Hostname Configuration
↓
Production Ready

## Requirements

- Ansible
- community.vmware
- pyvmomi
- sshpass

## Installation

```bash
ansible-galaxy collection install community.vmware
pip install pyvmomi
apt install sshpass
```

## Run

```bash
ansible-playbook playbooks/main.yml
```
