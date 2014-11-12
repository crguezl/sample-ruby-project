task :default => :spec

desc "run specs"
task :spec do
  sh "bundle exec rspec spec"
end

desc "Install groonga on a mac using brew"
task :groonga do
  sh "brew install groonga"
end

desc "open github repo in the browser"
task :open do
  sh "https://github.com/crguezl/sample-ruby-project"
end

desc "run the server"
task :server do
  sh "rackup"
end
