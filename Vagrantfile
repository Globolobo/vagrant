require 'yaml'

Vagrant.configure(2) do |config|

  config.vm.define "centos" do |centos|
    centos.vm.box = "centos/7"
    centos.vm.provision "shell",
      path:"./vagrant_sh/centos/node_v6.sh"
  end
  config.vm.define "ubuntu" do |ubuntu|
    ubuntu.vm.box = "ubuntu/xenial64"
    ubuntu.vm.provision "shell",
      path:"./vagrant_sh/ubuntu/node_v6.sh"
  end

end
