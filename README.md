# Ansible-playbook
Website deployment using Ansible Playbook

Playbook contains:
#1 configuration of services like httpd, firewalld, mariadb-server, php
#2 configuring firewalld ports
#3 creating database, users and executing sql scripts
#4 clone git code for website
#5 make changes to index.php file
#6 curl and check the connectivity

# and we're ready to go
#7 run the ansible playbook using cmd : ansible-playbook automation-deployment.yml
#8 for dry-run use : ansible-playbook automation-deployment.yml --check

# ensure to have firewall-python module for ansible, pymysql packages for proper functionining of ansible


