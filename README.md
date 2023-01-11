# Holiday-project
These are the files contained within the bastion host. 
The playbook and associated files let you configure the private instances before you associate them to an auto-scaling group, complete with load-balancing.

## ansible.cfg
The ssh-key and inventory locations are declared here.

## index.php
This contains the file to be stored in the site folder.

## inventory
This plays a role in the initial stages of this project. After the instance is set up, you create an AMI and then a Launch Template, which is then attached to your newly created auto-scaling group.
