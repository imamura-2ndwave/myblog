Vagrant.configure("2") do |config|

  config.vm.box = "centos/7"
  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.synced_folder ".", "/vagrant", disabled: true
  config.vm.synced_folder ".", "/var/www/laravel", create: true, owner: 'apache', group: 'apache', mount_options: ['dmode=777', 'fmode=777']

end
