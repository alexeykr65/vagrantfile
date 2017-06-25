# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "centos/7"

  config.vm.network "public_network"

  # config.vm.synced_folder "../data", "/vagrant_data"

  config.vm.provider "virtualbox" do |vb|
    vb.name = "Centos7"
  #vb.cpu
  #   # Display the VirtualBox GUI when booting the machine
  #   vb.gui = true
  #
  #   # Customize the amount of memory on the VM:
  #   vb.memory = "1024"
  end
  # config.vm.provision "shell", inline: <<-SHELL
  #   apt-get update
  #   apt-get install -y apache2
  # SHELL
  #config.vm.network :forwarded_port, guest: 22, host: 2201, id: 'ssh'
  config.vm.hostname = "centos"
  #config.ssh.username = 'root'
  #config.ssh.password = 'password'
  config.ssh.forward_x11 = true
  #config.ssh.port = 2201
  #config.ssh.insert_key = 'true'
end
