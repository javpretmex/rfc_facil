require 'bundler/gem_tasks'
require 'rake/testtask'

Rake::TestTask.new do |t|
  t.libs << 'tests'
  t.pattern = 'tests/*.rb'
end

desc 'Run tests'
task default: :test
