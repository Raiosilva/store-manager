source 'https://rubygems.org'
git_source(:github) { |repo| 'https://github.com/#{repo}.git' }

ruby '3.1.2'

gem 'rails', '~> 7.0.4'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'knock'
gem 'jwt'
gem 'rack-cors'
gem 'rack-attack'
gem 'bcrypt', '~> 3.1.7'
gem 'will_paginate'
gem 'bootsnap', require: false

group :test do
  gem 'factory_bot_rails'
  gem 'ffaker'
  gem 'database_cleaner'
end

group :development, :test do
  gem 'debug', platforms: %i[ mri mingw x64_mingw ]
  gem 'rspec-rails'
  gem 'rspec-json_expectations'
end

group :development do
  gem 'spring'
  gem 'listen'
end

gem 'tzinfo-data', platforms: %i[ mingw mswin x64_mingw jruby ]