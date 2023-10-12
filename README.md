# Welcome to **Ansible** Playbooks for network engineers 
---
### 1. Please make sure you install cisco module using command below
    ansible-galaxy collection install cisco.ios 
### 2. Assuming you already have inventory file and have basic knowledge of ansible

### 3. Make sure Network device is configured to allow ssh logins

### 4. Playbook exampple
    ansible-playbook -i inventory.ini Getarp.yml -K
--K will prompt for username and password to be used for network device.
