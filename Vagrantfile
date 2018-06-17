# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.synced_folder "/space", "/space", owner: "imiell", group: "imiell"
  config.vm.provider "virtualbox" do |vb|
    vb.gui = true
    vb.memory = "2048"
    vb.customize ['modifyvm', :id, '--clipboard', 'bidirectional'] 
  end
end
