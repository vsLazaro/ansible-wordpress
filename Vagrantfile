
Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/bionic64"

  config.vm.provider "virtualbox" do |v|
	v.memory = 1024
  end

  config.vm.define "wordpress" do |m|
	m.vm.network "private_network", ip: "192.168.56.21"
  end

  config.vm.define "mysql" do |m|
  m.vm.network "private_network", ip: "192.168.56.22"
  end

end
