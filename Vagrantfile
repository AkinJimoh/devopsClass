# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  
    config.vm.define "master" do |master|
      master.vm.box = "ubuntu/bionic64"
      master.vm.box_version = "20210928.0.0"
      master.vm.hostname = "master"
      master.vm.network "private_network", ip: "192.168.56.4"
    end
end