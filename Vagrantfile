Vagrant.configure("2") do |config|
    config.vm.define "web" do |web|
        web.vm.box="centos/7"
        web.vm.network "private_network", type: "dhcp"
        web.vm.hostname="web"
    end
    
    config.vm.define "db" do |db|
        db.vm.box="centos/7"
        db.vm.network "private_network", type: "dhcp"
        db.vm.hostname="db"
    end
    
    config.vm.define "pro" do |pro|
        pro.vm.box="centos/7"
        pro.vm.network "private_network", type: "dhcp"
        pro.vm.hostname="provision"
    end
end
