# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  # Basics
  config.vm.box = "debian-7.2.0"
  config.vm.box_url = "https://dl.dropboxusercontent.com/u/197673519/debian-7.2.0.box"
  config.vm.network "private_network", ip: "192.168.100.10"
  config.ssh.forward_agent = true

  # Provisioning
  salt_folder = "salt-from-scratch"
  config.vm.synced_folder salt_folder, "/srv/salt", type: "nfs"
  config.vm.provision :salt do |salt|
      salt.minion_config = salt_folder + "/minion"
      salt.run_highstate = true
      salt.verbose = true
  end

  # Workarounds
  config.vm.synced_folder ".", "/vagrant", type: "nfs"

end
