# based on https://github.com/erran-r7/multiple_vagrantfiles

# all
vagrantfiles = %w[../h-platform-automation-cm/Vagrantfile ../h-platform-automation-monitoring/Vagrantfile ../h-platform-automation-website/Vagrantfile ../h-platform-automation-tracing/Vagrantfile]
#vagrantfiles = %w[../h-platform-automation-monitoring/Vagrantfile ../h-platform-automation-website/Vagrantfile ../h-platform-automation-tracing/Vagrantfile]
# tracing, website, jenkins and proxmox
#vagrantfiles = %w[../h-platform-automation-tracing/Vagrantfile ../h-platform-automation-website/Vagrantfile ../h-platform-automation-cm/Vagrantfile]
# only jenkins and proxmox
#vagrantfiles = %w[../h-platform-automation-cm/Vagrantfile]
# only monitoring and tracing
#vagrantfiles = %w[../h-platform-automation-monitoring/Vagrantfile ../h-platform-automation-tracing/Vagrantfile]
# only tracing and website
#vagrantfiles = %w[../h-platform-automation-tracing/Vagrantfile ../h-platform-automation-website/Vagrantfile]
# only monitoring
#vagrantfiles = %w[../h-platform-automation-monitoring/Vagrantfile]
# only tracing
#vagrantfiles = %w[../h-platform-automation-tracing/Vagrantfile]
# only website
#vagrantfiles = %w[../h-platform-automation-website/Vagrantfile]

vagrantfiles.each do |vagrantfile|
  load File.expand_path(vagrantfile) if File.exists?(vagrantfile)
end
