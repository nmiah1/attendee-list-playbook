# Ansible Workshop Attendee List Playbook 
Pre-reqs


Running the playbook
Run the playbook as follows. You mght need additional flags to specify ssh user etc

example for a workshop environment ...

ansible-playbook -i student1.abcd.rhdemo.io, install_rocket.yml -u student1 -k -e @extra_vars

example for your own instance in ec2 ...

ansible-playbook -i rocket.mydomain.com, install_rocket.yml -u ec2-user --private-key=~/.ssh/id_rsa -e @extra_vars
