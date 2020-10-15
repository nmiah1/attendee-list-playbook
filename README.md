# Ansible Workshop Attendee List to CSV Playbook 
## What does this playbook do? 
This playbook will record down the attendees name and emails from the Ansible Wokrshop and store it in a CSV.

## Pre-reqs
1. Make sure that the workshop is fully provionsed. 
2. You have access to the login url for the workshop for example http://login.d98x.open.redhat.com/list.php
3. Ansible installed on your host machine

## Running the playbook
Run the playbook as follows. 

Example for workshop environment ...

```bash
ansible-playbook list2.yml
What is the workshop URL? An example would be http://login.d98x.open.redhat.com/list.php: http://login.a76d.open.redhat.com/list.php
What is the workhop student password?: cNQn9ZxY9pAHYx
```

## Result 
attendee-list-{workshop-date}.csv 
