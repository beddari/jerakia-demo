# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.provision "file", source: "./", destination: "$HOME/"
  config.vm.provision "shell", path: "setup.sh"
end
