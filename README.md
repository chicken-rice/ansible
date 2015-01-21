ansible
=======
config.vm.define :node1 do |node|
    node.vm.box = "ubuntu/precise64"
    node.vm.network :private_network, ip: "192.168.33.11"
  end

  config.vm.define :node1 do |node|
    node.vm.box = "ubuntu/precise64"
    node.vm.network :private_network, ip: "192.168.33.12"
  end
