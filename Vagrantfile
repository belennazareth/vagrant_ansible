
 Vagrant.configure("2") do |config|
      nodo1.vm.box = "debian/bullseye64"
      nodo1.vm.hostname = "nodo1"
    end
    
 end

  Vagrant.configure("2") do |config|
    config.vm.box = "debian/bullseye64"
    config.vm.synced_folder ".", "/vagrant", disabled: true
    config.vm.define :router do |router|
      router.vm.box = "debian/bullseye64" 
      router.vm.hostname = "router" 
    config.vm.provider :libvirt do |libvirt|
      libvirt.memory = 1024
      libvirt.cpus = 2
    end
end
