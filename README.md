# VagrantEnvironments

	1. Arch Linux with VirtualBox

### Useful Vagrant Commands

	$ vagrant up (start)
	$ vagrant ssh (login)
	$ vagrant provision (test provisioners)
	$ vagrant halt (stop)
	$ vagrant suspend (suspend)
	$ vagrant reload (restart)
	$ vagrant upgrade (upgrade)

### Linux Commands

	1. ArchLinux
	
		- Admin
		$ sudo su

		- Tmate
		$ pacman -S tmate # Install
		$ ssh-keygen # Generate ssh keys (-t rsa)
		$ tmate # Start tmate
		$ tmate show-messages # Show tmate ssh session id
		$ ssh <ssh_session_id> # Connect via ssh
		$ exit # Close connection
