Vagrant.configure("2") do |config|
  config.vm.box = "stf-poc"
  config.vm.network "private_network", ip: "192.168.1.101"
  config.ssh.insert_key = false
  config.vm.provider "virtualbox" do |v|
     v.customize [ "modifyvm", :id, "--uartmode1", "disconnected" ] # disable the log file output
     v.memory = 2048
     v.cpus = 2
  end
end