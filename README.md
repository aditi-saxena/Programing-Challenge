# Programing-Challenge

Application URL: http://20.219.252.194:3000/

Files in repo
-Hosts
-Playbook.yml
-Dcokercompose.yml


Steps:
1. Created Ubuntu 18.04 Vm on Azure Cloud to make it a ansible workstation
2. created Ubuntu 18.04 Vm on Azure CLoud to make it Slave machine
3. Installed Ansible in Ansible Workstation and added tusted host with help of sshpass key
4. Download App to be deployed on Ansible Workstation
5. created ansible playbook to do tasks(playbook.yml):
  a.copying app files from workstation slave
  b.Install required system packages(pip, python3 etc)
  c.Add Docker GPG apt Key
  d. Add Docker Repository
  e. Install Docker Compose
  f. Run Docker compose(Dockercompose.yml)
  
