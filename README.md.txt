This script is going to copy the key file on the server, the list of 100 servers should be put on host files on ansible.

The below command is assuming you have an inventory of 100 servers and your playbook is stored in ansible directory

Steps to run
1. ansible-playbook playbook.yml  --syntax-check
2. ansible-playbook playbook.yaml -e "user=root"