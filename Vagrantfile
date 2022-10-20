#-----------------------------------------------
# Crear una máquina virtual debian de nombre prueba
#-----------------------------------------------

#Vagrant.configure("2") do |config|
#    config.vm.box = "debian/bullseye64"
#    config.vm.hostname="prueba"
#    config.vm.synced_folder ".", "/vagrant", disabled: true
#end

#-----------------------------------------------
# Crear dos máquinas debian y ubuntu de nombre nodo1 y nodo2
#-----------------------------------------------

# Vagrant.configure("2") do |config|

#    config.vm.define :nodo1 do |nodo1|
#      nodo1.vm.box = "debian/bullseye64"
#      nodo1.vm.hostname = "nodo1"
#    end
#    config.vm.define :nodo2 do |nodo2|
#      nodo2.vm.box = "generic/ubuntu2010"
#      nodo2.vm.hostname = "nodo2"
#    end
# end

#-----------------------------------------------
# Crear una máquina debian de nombre prueba modificando RAM y CPU
#-----------------------------------------------

  Vagrant.configure("2") do |config|
    config.vm.box = "debian/bullseye64"
    config.vm.hostname="prueba"
    config.vm.synced_folder ".", "/vagrant", disabled: true
    config.vm.provider :libvirt do |libvirt|
      libvirt.memory = 1024
      libvirt.cpus = 2
    end
end
