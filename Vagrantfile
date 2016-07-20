Vagrant.configure(2) do |config|
  config.vm.define "manager1" do |manager1| 
  	manager1.vm.box = "ubuntu/trusty64"
  	manager1.vm.network "public_network" , :adapter=>2 , type: "dhcp", :bridge => "eth0"
  	manager1.vm.hostname ="manager1"
  	manager1.vm.provider "virtualbox" do |vb|
  #   # Display the VirtualBox GUI when booting the machine
    vb.gui = true
    vb.name = "manager1"
     # Customize the amount of memory on the VM:
    vb.memory = "512"
    end 
end
  config.vm.define "manager2" do |manager2| 
    manager2.vm.box = "ubuntu/trusty64"
    manager2.vm.network "public_network" , :adapter=>2 , type: "dhcp", :bridge => "eth0"
    manager2.vm.hostname ="manager2"
    manager2.vm.provider "virtualbox" do |vb|
  #   # Display the VirtualBox GUI when booting the machine
    vb.gui = true
    vb.name = "manager2"
     # Customize the amount of memory on the VM:
    vb.memory = "512"
    end 
end
  config.vm.define "manager3" do |manager3| 
    manager3.vm.box = "ubuntu/trusty64"
    manager3.vm.network "public_network" , :adapter=>2 , type: "dhcp", :bridge => "eth0"
    manager3.vm.hostname ="node1"
    manager3.vm.provider "virtualbox" do |vb|
  #   # Display the VirtualBox GUI when booting the machine
    vb.gui = true
    vb.name = "manager3"
     # Customize the amount of memory on the VM:
    vb.memory = "512"
    end 
end
end

