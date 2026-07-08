# VMware VM Provisioning Automation using Ansible

Enterprise automation project for provisioning and configuring VMware virtual machines.

## Features

- Cross-vCenter VM cloning
- Automatic VM power-on
- Network configuration
- Hostname configuration
- Multi-VM provisioning
- VMware infrastructure automation

## Technologies

- Ansible
- VMware vSphere
- community.vmware
- Oracle Linux
- SSH
- VMware ESXi

## Architecture

Template Clone
↓
Power On
↓
Configure Network
↓
Configure Hostname
↓
Ready To Use VM

## Requirements

- Ansible
- community.vmware
- pyvmomi
- sshpass

## Run

```bash
ansible-playbook playbooks/main.yml
