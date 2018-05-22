source 'http://rubygems.org'
ruby '2.4.1'

gem 'sinatra'
gem 'activerecord', '~> 4.2', '>= 4.2.6', :require => 'active_record'
gem 'sinatra-activerecord', :require => 'sinatra/activerecord'
gem 'rake'
gem 'require_all'
gem 'bcrypt'
gem 'rack-flash3'
gem 'thin'
gem 'pg', '~> 1.0'


group :development do
 gem "tux"
 gem 'pry'
 gem 'shotgun'
end

group :production do
 
end



group :test do
  gem 'rspec'
  gem 'capybara'
  gem 'rack-test'
  gem 'database_cleaner', git: 'https://github.com/bmabey/database_cleaner.git'
end
