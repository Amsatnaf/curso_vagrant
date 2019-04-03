vagrant.configure("2") do |config|

	config.vm.porevider "virtualbox"
	
	config.vm.difine :curso_vagrant do |curso_vagrant_config|
		#usando ubuntu 18.04
		curso_vagrant_config.vm.box = "ubuntu/bionic64"
		curso_vagrant_config.vm.network = "private_network", ip: "192.168.50.12"
	end
end
              

		
