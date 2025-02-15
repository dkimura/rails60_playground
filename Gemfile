# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

gem 'rails', '~> 6.0.0'

gem 'puma', '~> 3.11'

gem 'sqlite3', '~> 1.4'

gem 'config'
gem 'jbuilder', '~> 2.7'
gem 'slim-rails'

gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  gem 'dotenv-rails'

  gem 'pry-byebug'
  gem 'pry-coolline'
  gem 'pry-doc'
  gem 'pry-rails'
  gem 'pry-stack_explorer'

  gem 'factory_bot_rails'
  gem 'rspec-rails'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'

  gem 'brakeman', require: false
  gem 'rubocop', require: false
  gem 'rubocop-checkstyle_formatter', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false

  gem 'web-console', '>= 3.3.0'

  gem 'annotate'
  gem 'rails-erd'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end
