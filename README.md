# Ansible-playbook
Website deployment using Ansible Playbook

Playbook contains:

-> configuration of services like httpd, firewalld, mariadb-server, php

-> configuring firewalld ports

-> creating database, users and executing sql scripts

-> clone git code for website

-> make changes to index.php file

-> curl and check the connectivity

# and we're ready to go
-> run the ansible playbook using cmd : ansible-playbook automation-deployment.yml

-> for dry-run use : ansible-playbook automation-deployment.yml --check

# ensure to have firewall-python module for ansible, pymysql packages for proper functionining of ansible


