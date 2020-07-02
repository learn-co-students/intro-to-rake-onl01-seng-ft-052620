# task :environment do
#   require_relative
#   './config/environment'
# end
namespace :greetings do
desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end

desc 'outputs hola to terminal'
  task :hola do
    puts "hola de rake"
  end
end

namespace :db do
  desc 'migrate changes to your database'
    task :migrate => :environment do
      Student.create_table
    end
end

task :environment do
  require_relative
  './config/environment'
end
  
  desc "adds seed data to database"
    task :seed do
      require_relative ./db/seeds.rb
    end

# task :environment do
#   require_relative
#   './config/environment'
# end