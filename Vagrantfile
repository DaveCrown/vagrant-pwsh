
Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.provision "shell", inline: "sudo yum -y install epel-release"
  config.vm.provision "shell", inline: "sudo yum -y install ansible"
  config.vm.provision "shell", inline: "cd /vagrant && ansible-playbook install.yml"
end
