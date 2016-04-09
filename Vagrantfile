Vagrant.configure("2") do |config|

    # main & default: normal OS series...
    config.vm.define "main", primary: true do |node|
        node.vm.box = "bento/centos-7.2"
        node.vm.network "private_network", ip: "10.0.0.10"

        node.vm.provision "ansible" do |ansible|
            ansible.playbook = "setup.yml"
            ansible.sudo = true
        end
    end

end
