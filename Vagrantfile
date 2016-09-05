# -*- mode:ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.ssh.insert_key = false
  config.vm.define "loadbalancer" do |loadbalancer|
    loadbalancer.vm.box = "bento/centos-6.7"
    loadbalancer.vm.network "private_network", ip: "192.168.11.10"
  end
  config.vm.define "webserver1" do |webserver1|
    webserver1.vm.box = "bento/centos-6.7"
    webserver1.vm.network "private_network", ip: "192.168.11.11"
  end
  config.vm.define "webserver2" do |webserver2|
    webserver2.vm.box = "bento/centos-6.7"
    webserver2.vm.network "private_network", ip: "192.168.11.12"
  end
  config.vm.define "dbserver" do |dbserver|
    dbserver.vm.box = "bento/centos-6.7"
    dbserver.vm.network "private_network", ip: "192.168.11.21"
  end
end

