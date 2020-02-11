# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "CentOS7"
  # ホスト名
  config.vm.hostname = "centos7.vm"
  # ネットワーク
  config.vm.network "private_network", ip: "192.168.33.30"

  config.vm.synced_folder "./shared", "/var/www/html/shared", owner: "apache", group: "apache", mount_options: ['dmode=777','fmode=755']
  config.vm.synced_folder "./backbone-schoo", "/var/www/html/backbone-schoo", owner: "apache", group: "apache", mount_options: ['dmode=777','fmode=755']
  config.vm.synced_folder "./jquery-highest", "/var/www/html/jquery-highest", owner: "apache", group: "apache", mount_options: ['dmode=777','fmode=755']
  config.vm.synced_folder "./jquery-honkaku", "/var/www/html/jquery-honkaku", owner: "apache", group: "apache", mount_options: ['dmode=777','fmode=755']
  config.vm.synced_folder "./jquery-udemy", "/var/www/html/jquery-udemy", owner: "apache", group: "apache", mount_options: ['dmode=777','fmode=755']
  config.vm.synced_folder "./jquery-dojo", "/var/www/html/jquery-dojo", owner: "apache", group: "apache", mount_options: ['dmode=777','fmode=755']
  config.vm.synced_folder "./started-vue", "/var/www/html/started-vue", owner: "apache", group: "apache", mount_options: ['dmode=777','fmode=755']
  config.vm.synced_folder "./basic-vue", "/var/www/html/basic-vue", owner: "apache", group: "apache", mount_options: ['dmode=777','fmode=755']
  config.vm.synced_folder "./sokushu-vue", "/var/www/html/sokushu-vue", owner: "apache", group: "apache", mount_options: ['dmode=777','fmode=755']
  config.vm.synced_folder "./vue-nuxt", "/var/www/html/vue-nuxt", owner: "apache", group: "apache", mount_options: ['dmode=777', 'fmode=755']
  config.vm.synced_folder "./vue-crud", "/var/www/html/vue-crud", owner: "apache", group: "apache", mount_options: ['dmode=777', 'fmode=755']	
  config.vm.synced_folder "./vue-todo", "/var/www/html/vue-todo", owner: "apache", group: "apache", mount_options: ['dmode=777', 'fmode=755']
  config.vm.synced_folder "./frontend-techacademy", "/var/www/html/frontend-techacademy", owner: "apache", group: "apache", mount_options: ['dmode=777', 'fmode=755']
end
