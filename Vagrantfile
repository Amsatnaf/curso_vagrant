Vagrant.configure("2") do |config|

  config.vm.provider "virtualbox"

 config.vm.define :curso do |curso_config|
    #usando ubuntu 18.04
                curso_config.vm.box = "ubuntu/bionic64"
                curso_config.vm.network "private_network", ip: "192.168.50.10"
    curso_config.vm.provision "shell", path: "manifests/install.sh"
                curso_config.vm.provision "puppet" do |puppet|
       puppet.manifest_file = "curso.pp"
    end
        end

end
          

		
