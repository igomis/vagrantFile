Vagrant.configure("2") do |config|
   config.vm.box = "Ignasi/dwes"
   config.vm.network "private_network", ip: "192.168.99.10"
   config.ssh.password = "vagrant"
   config.vm.synced_folder "../code", "/code"
end
