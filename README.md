This is an Ansible project to install Spring-XD on CentOS.  To change this to an apt-based system install you will just have to switch most yum commands to apt commands.

To install all components of Spring-XD on CentOS Vagrant cluster:

	vagrant up
	ansible-playbook spring-xd-playbook.yml -i vagrant-inventory.ini
