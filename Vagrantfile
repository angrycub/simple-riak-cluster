# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"
Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.box = "chef/centos-6.5"
  config.vm.provision "riak", type: "shell", path: "bin/provision_riak.sh"
  config.vm.network "private_network", type: "dhcp"

  config.vm.define "node1" do |node1|
    node1.vm.hostname = "node1.riak.local"
  end

  config.vm.define "node2" do |node2|
    node2.vm.hostname = "node2.riak.local"
  end

  config.vm.define "node3" do |node3|
    node3.vm.hostname = "node3.riak.local"
  end

end
