## Deploying Nagios Agent (NRPE) using Ansible

hosts file
------------

hosts file in this repo has the list of ip-addresses with the key-pair path and user name, is a reference for how to connect to aws ec2 instances. 

Note: This hosts file is just for our knowledge, how to give key-pair and user name. Please update your hosts file located at /etc/ansible/hosts. 

configure-nrpe
------------

This is an ansible role, which consists of ansible role directory structure and files. 

execute this ansible role
-------------------------

ansible-playbook nrpe-server.yml
