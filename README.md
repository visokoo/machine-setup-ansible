# machine-setup-ansible
Simple ansible playbooks just to set up the menial stuff...

#### Pi - When it boots up, run these commands:
1. ssh-copy-id ubuntu@172.16.110.48
	* If you get ""SSH2_MSG_KEXINIT sent," try running: 
 	*`sudo rm /etc/ssh/ssh_host_*`
 	*`sudo dpkg-reconfigure openssh-server`
2. apt-get install -y python