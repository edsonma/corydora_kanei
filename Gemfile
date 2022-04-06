source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.4', '>= 6.1.4.7'
# Use Puma as the app server
gem 'puma', '~> 5.0'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'
gem 'mongoid', '~> 7.3.0'
# MongoId for good
# Cleaner view templating language
gem 'slim'
gem 'slim-rails'
# bootstrapping
gem 'bootstrap', '~> 5.1.3'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  # RSpec for Rails-3+
  # Needed because of https://github.com/rspec/rspec-rails/pull/2089
  # TODO: Consider removing when 4.0 is officialy released
  gem 'rspec-collection_matchers' # More matchers
  gem 'rspec-rails', '~> 5.0.1'
  # RSpec matchers and macros for Mongoid.
  gem 'mongoid-rspec'
  # A library for setting up Ruby objects as test data
  gem 'factory_bot_rails'
  gem 'ffaker'
  # Ruby code quality scanner
  gem 'rubocop', require: false
  # Integration with RSpec
  gem 'rubocop-rspec', '~> 2.3.0', require: false
  # rubocop rails cops
  gem 'rubocop-rails'
  # rubocop performance cops
  gem 'rubocop-performance'
  # code vulnerabilities scan
  gem 'brakeman'
  # Yet Another code quality scanner
  gem 'reek'
  # Library for stubbing and setting expectations on HTTP requests in Ruby.
  gem 'webmock'
  # Ability to freeze time itself
  gem 'timecop'
  # Loads environment variables from a .env file
  gem 'dotenv-rails'
  # Manage Procfile-based applications http://ddollar.github.com/foreman
end

group :development do
  gem 'listen', '~> 3.3'
end

group :test do
  gem 'database_cleaner-mongoid'
  gem 'fuubar'
  # matchers to check controller templates
  gem 'rails-controller-testing' 
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
