
Vagrant.configure("2") do |config|
  config.vm.box = "generic/ubuntu2004"
  config.vm.synced_folder ".", "/vagrant", type: "rsync", rsync__exclude: ".git/"
  config.ssh.extra_args = ["-t", "cd /vagrant; bash --login"]
end
