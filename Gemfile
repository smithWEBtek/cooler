source 'https://rubygems.org'
git_source(:github) { |repo| 'https://github.com/#{repo}.git' }

ruby '2.7.1'
# gem 'activesupport', '~> 5.2', '>= 5.2.4.4'
gem 'activesupport'
gem 'pdf-reader'
gem 'mailgun'
gem 'rails-erd'
gem 'pry-rails'
gem 'watir'
gem 'nokogiri', '>=1.5.9'
gem 'httparty'
gem 'faraday'
gem 'thor', '~> 0.19.0'
gem 'yaml_db'
gem 'jquery-rails'
gem 'rack-cors', :require => 'rack/cors'
gem 'seed_dump'	
gem 'mechanize', '~> 2.7', '>= 2.7.5'

gem 'rails', '~> 5.2'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'pg', '>= 0.18', '< 2.0'
gem 'font-awesome-rails'
gem 'webpacker'
gem 'dotenv-rails', :groups => [:development, :test]
gem 'active_model_serializers'
gem 'http'

gem 'jbuilder', '~> 2.5'
gem 'bcrypt', '~> 3.1.7'

gem 'capistrano', '~> 3.11', require: false
gem 'capistrano-rails', '~> 1.3', require: false
gem 'capistrano-bundler'
gem 'capistrano-passenger'
gem 'capistrano-rvm'
gem 'ed25519', '>= 1.2'
gem 'bcrypt_pbkdf', '>= 1.0'

# for generation of PDF files from Rails views
# gem 'nokogiri', :git => 'https://github.com/tenderlove/nokogiri.git'
# https://github.com/mileszs/wicked_pdf
# gem 'wicked_pdf', :git => 'https://github.com/mileszs/wicked_pdf.git'
gem 'wicked_pdf'
# gem 'wkhtmltopdf-binary', :git => 'https://github.com/pallymore/wkhtmltopdf-binary.git'
gem 'wkhtmltopdf-binary'
gem 'bootstrap'

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'guard'
  gem 'guard-shell'
  gem 'web-console', '>= 3.3.0'
  gem 'foreman', '~> 0.82.0'
  gem 'pry'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
