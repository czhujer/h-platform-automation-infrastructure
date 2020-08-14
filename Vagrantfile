Vagrant.configure('2') do |config|
  config.ssh.max_tries = 40
  config.ssh.timeout   = 120
end

# all
vagrantfiles = %w[../h-platform-automation-cm/Vagrantfile ../h-platform-automation-monitoring/Vagrantfile ../h-platform-automation-website/Vagrantfile]
# only jenkins and proxmox
#vagrantfiles = %w[../h-platform-automation-cm/Vagrantfile]
# only monitoring
#vagrantfiles = %w[../h-platform-automation-monitoring/Vagrantfile]
# only website
#vagrantfiles = %w[../h-platform-automation-website/Vagrantfile]

vagrantfiles.each do |vagrantfile|
  load File.expand_path(vagrantfile) if File.exists?(vagrantfile)
end
