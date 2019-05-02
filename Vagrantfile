Vagrant.configure(2) do |config|

  config.vm.define "node1" do |node1|
  node1.vm.box = "bento/centos-6.7"
  node1.vm.hostname = 'node1'
  node1.vm.network :private_network, ip: "192.168.56.90"
  config.vm.provider "virtualbox" do |v|
  config.vm.synced_folder ".", "/home/vagrant"
 end
  end

  
  config.vm.define "node2" do |node2|
  node2.vm.box = "bento/centos-7.5"
  node2.vm.hostname = 'node2'
  node2.vm.network :private_network, ip: "192.168.56.92"
  config.vm.synced_folder ".", "/home/vagrant"
  end
  
  config.vm.define "node3" do |node3|
  node3.vm.box = "bento/centos-7.5"
  node3.vm.hostname = 'node3'
  node3.vm.network :private_network, ip: "192.168.56.93"
 
 end
 
 config.vm.define "node4" do |node4|
  node4.vm.box = "bento/centos-7.5"
  node4.vm.hostname = 'node4'
  node4.vm.network :private_network, ip: "192.168.56.94"
  
  end
  
  config.vm.define "node5" do |node5|
  node5.vm.box = "bento/centos-7.1"
  node5.vm.hostname = 'node5'
  node5.vm.network :private_network, ip: "192.168.56.95"
  
  end
   config.vm.define "node6" do |node6|
  node6.vm.box = "bento/centos-7.1"
  node6.vm.hostname = 'node6'
  node6.vm.network :private_network, ip: "192.168.56.96"
  
  end
  
  
  config.vm.define "node7" do |node7|
  node7.vm.box = "ubuntu/trusty64"
  node7.vm.hostname = 'node7'
  node7.vm.network :private_network, ip: "192.168.56.97"
 
 end

  config.vm.define "node8" do |node8|
    node8.vm.box = "ubuntu/trusty64"
      node8.vm.hostname = 'node8'
        node8.vm.network :private_network, ip: "192.168.56.98"

end
end
