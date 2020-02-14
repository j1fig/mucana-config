# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "chingc/win10"
  config.vm.communicator = "winrm"
  config.vm.guest = "windows"

  config.winrm.username = "IEUser"
  config.winrm.password = "Passw0rd!"
  config.winrm.timeout = 180

  config.ssh.username = "IEUser"
  config.ssh.password = "Passw0rd!"
  config.ssh.extra_args = "powershell"  # cmd or powershell
end
