require 'rubygems'
require 'rake'
require 'yaml'
require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new do |t|
  t.pattern = 'spec/**/*_spec.rb'
end

task :default => :spec