Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-18.04"

  config.vm.define :web_a do |host|
    host.vm.hostname = "web-a"
    host.vm.network :private_network, ip: "192.168.33.10"  
  end

  config.vm.define :dns_a do |host|
    host.vm.hostname = "dns-a"
    host.vm.network :private_network, ip: "192.168.33.20"
  end

  config.vm.define :rev_proxy_a do |host|
    host.vm.hostname = "rev-proxy-a"
    host.vm.network :private_network, ip: "192.168.33.30"
  end

  config.vm.define :db_a do |host|
    host.vm.hostname = "db-a"
    host.vm.network :private_network, ip: "192.168.33.40"
  end
end
