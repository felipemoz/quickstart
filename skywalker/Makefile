export os='ubuntu'

install:
	make prepare
	cd ${os} && ansible-playbook ubuntu.yml --become

prepare:
	sudo apt update 
	sudo apt install ansible -y 



