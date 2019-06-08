Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
 #config.vm.provision :shell, path: "bootstrap.sh"
 #config.vm.network :forwarded_port, guest: 80, host: 4567
  config.vm.provision :ansible do |ansible|
    ansible.playbook = "provisioning/playbook.yml"
  end
end
