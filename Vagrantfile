Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/bionic64"
  config.vm.network "private_network", ip: "192.168.10.100"
  config.hostsupdater.aliases = ["jenkinsbox.local"]
  config.vm.provision "shell", path: "provision.sh"

end
