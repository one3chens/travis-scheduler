require 'rake'

task default: :spec

namespace :db do
  desc 'Create the test database'
  task :create do
    sh 'psql -q < spec/support/db/create.sql'
  end
end

