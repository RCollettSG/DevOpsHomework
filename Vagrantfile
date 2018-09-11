# if Vagrant.has_plugin?("vagrant-hostsupdater")
#   system "vagrant plugin install vagrant-hostsupdater"
# else
#   puts "Plugin installed already"
# end

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.network("private_network", ip: "192.168.10.100")
  config.hostsupdater.aliases = ["development.local"]
end
