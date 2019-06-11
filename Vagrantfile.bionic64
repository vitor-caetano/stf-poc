Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"
  config.vm.network "private_network", ip: "192.168.1.101"
  config.ssh.insert_key = false
  config.vm.provider "virtualbox" do |v|
     v.memory = 2048
     v.cpus = 2
  end
end
