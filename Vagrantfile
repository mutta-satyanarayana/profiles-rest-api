VAGRANTFILE_API_VERSION = "2"
Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "testbox"
  config.vm.network :private_network, ip: "192.168.50.102"
  config.vm.provider :virtualbox do |vb|
    vb.gui = true
  end
end