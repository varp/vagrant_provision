task :install do
  system "#{Dir.chdir('..')} && vagrant destroy"
  system "cd #{Dir.chdir('vagrant_provision')} && git reset --hard && git pull && cd #{Dir.chdir('..')}"
  system 'cp -vf vagrant_provision/Vagrantfile .' 
end

task :build do
  puts "Building"
end