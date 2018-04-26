# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.define "vag01" do |vag01|
    vag01.vm.box = "centos/7"
    vag01.vm.network "forwarded_port",guest:80,host:8080
  end

end
