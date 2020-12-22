Vagrant.configure("2") do |config|
  # Box type
  config.vm.box = "generic/arch"
  # Hostname
  config.vm hostname = "laboratory"
  # Docker management
  config.vm.provision "docker"
  # Memory management
  config.vm.provider "virtualbox" do |vb|
  	# Memory limit
  	vb.memory = "10240"
	# CPUs limit
	vb.cpus = 3
	# Max CPUs
	vb.customize ["modifyvm", :id, "--cpuexecutioncap", "75"]
  end
end
