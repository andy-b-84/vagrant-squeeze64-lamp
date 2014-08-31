VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "andy_b_84/debian-squeeze64-lamp"
  config.vm.network "forwarded_port", guest: 80, host: 8080
end
