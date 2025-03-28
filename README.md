# Automated Configuration Management for Telecom Networks

## Overview
This project automates network device configuration using Ansible. It helps telecom engineers manage routers and switches efficiently.

## Features
- Bulk configuration deployment
- Secure authentication
- Modular Ansible roles

## Installation
1. Install Ansible: `pip install ansible`
2. Update `inventory.ini` with device details.
3. Run the playbook: `ansible-playbook playbook.yml`

## Structure
- `ansible.cfg` - Ansible configuration
- `inventory.ini` - List of network devices
- `playbook.yml` - Main automation script
- `roles/` - Modular roles for configurations

## Future Enhancements
- Add SNMP monitoring
- Implement CI/CD integration

## License
MIT
