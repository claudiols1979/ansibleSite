# ansibleSite
deploy flask website with ansible and vagrant
# Getting Started:
# 1. vagrant plugin install vagrant-hostmanager
# 2. vagrant up
# 3. vagrant ssh
Vagrant files creates a private network and assign an ip address to all guess machines. 
Using VirtualBox as default. (Accepts, Docker, VMware and Hyper-v)

#SITE.YML
invoke all ansible roles through ansible.yml playbooks. 
#ansible-playbook site.yml

Vagrant file create 5 machines accessible through a ssh <machine_name>
lb01, app01, app02, db01, and control 

#CONTROL MACHINE 
ansible installation is required in order to shoot ansible commands. Vagrant box use for this environemnt is "ubuntu/trusty64" (Ubuntu 14). See ansible installation documentation for more details. 

https://docs.ansible.com/ansible/devel/installation_guide/intro_installation.html


Feel free to modify this file if you find more proper instructions can be added. 
