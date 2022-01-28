# Workstation Tools

> **Disclaimer** :
Those scripts are ubuntu related with major version 18+, for other distributions you'll need to adapt it

## Prepare Workstation
Read the ubuntu.yml file before applying and be sure to understand everything that will be done.

1. Install Ansible
```shell
sudo apt update && sudo apt install ansible unzip git -y
```
1. Clone this repository
```shell
git clone https://github.com/caiodelgadonew/tools.git
```
1. Apply the configuration
```shell
ansible-playbook tools/ubuntu.yml --ask-become-pass
```
