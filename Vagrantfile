VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.ssh.insert_key = false

config.vm.define "vagrant1" do |vagrant1|
  config.vm.box = "ubuntu/trusty64"
  config.vm.hostname = "node102"
  config.vm.network "private_network", ip: "192.168.33.102"
end

config.vm.define "vagrant2" do |vagrant2|
  config.vm.box = "ubuntu/trusty64"
  config.vm.hostname = "node103"
  config.vm.network "private_network", ip: "192.168.33.103"
end

config.vm.define "vagrant3" do |vagrant3|
  config.vm.box = "ubuntu/trusty64"
  config.vm.hostname = "node104"
  config.vm.network "private_network", ip: "192.168.33.104"
end

end