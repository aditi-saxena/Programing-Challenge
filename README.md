# Programing-Challenge

Application URL: http://20.219.252.194:3000/

Files in repo
Hosts
Playbook.yml
compose.yml


Steps:
Created Ubuntu 18.04 Vm on Azure Cloud to make it a ansible workstation
created Ubuntu 18.04 Vm on Azure CLoud to make it Slave machine
Installed Ansible in Ansible Workstation and added tusted host with help of sshpass key
Download App to be deployed on Ansible Workstation
created ansible playbook to do tasks(playbook.yml):
  copying app files from workstation slave
  Install required system packages(pip, python3 etc)
  Add Docker GPG apt Key
  Add Docker Repository
  Install Docker Compose
  Run Docker compose(Dockercompose.yml)
  
