Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty32"
  config.vm.network "forwarded_port", host: 8080, guest: 80
  config.vm.provision :shell, path: "bootstrap.sh"
end