# ansible_tutorial
This is beginner friendly guide for ansible

1. Learning ansible setup and ad hoc commands

Steps to install ansible

sudo apt install ansible

create inventory file

###################################
Ansible ad hoc commands

ansible -i inventory -m module-name -a 'argument' hosts

inventory = inventory.ini
module-name = shell, file, copy, command, yum, service
argument = df -h, path, state, src, dest, name
state = present, restarted, directory

to list all ansible modules
ansible-doc -l
ansilbe-doc [module name]
