Establish the SSH connection and test the connect with below command

	ansible all -i inventory.yml -m ping

Clone this repo to ansible-node

	git clone https://github.com/tryingtobecoder58/es-ansible-installation

Run the Ansible-Playbook
	
	ansible-playbook -i inventory.yml playbook.yml

