source 'https://rubygems.org'
git_source(:github) { |repo| 'https://github.com/#{repo}.git' }

gem 'rails', '~> 5.2'
ruby '2.7.6'

gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'rack-cors', :require => 'rack/cors'
gem 'webpacker'
gem 'dotenv-rails', :groups => [:development, :test]
# gem 'libv8-node', '~> 15.14'
gem 'active_model_serializers'

# gem 'activesupport', '~> 5.2', '>= 5.2.4.4'
gem 'activesupport'
gem 'actionview'
gem 'pdf-reader'
gem 'mailgun'
gem 'rails-erd'
gem 'pry-rails'
gem 'watir'
gem 'nokogiri', '~> 1.11'
gem 'httparty'
gem 'faraday'
gem 'thor', '~> 0.19.0'
gem 'yaml_db'
gem 'jquery-rails'
gem 'seed_dump'	
gem 'mechanize', '~> 2.7', '>= 2.7.5'

# gem 'sass-rails', '~> 5.0'
gem 'sass-rails'
gem 'uglifier', '>= 1.3.0'
gem 'font-awesome-rails'
gem 'http'
# gem 'mini_racer'

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
