source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.1'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# for autodetecting JavaScript
gem 'execjs'
gem 'mini_racer'
# not supported
# gem 'therubyracer'

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'

# friendy id gem for routes
gem 'friendly_id', '~> 5.1.0'

# authentication gem
gem 'devise', '~> 4.5'

# bootstrap 4.1.3 gem
gem 'bootstrap', '~> 4.1.3'

# jquery
gem 'jquery-rails', '~> 4.3', '>= 4.3.1'
# jquery ui
gem 'jquery-ui-rails', '~> 6.0', '>= 6.0.1'
# cocoon to work with jquery
gem 'cocoon', '~> 1.2', '>= 1.2.12'

# web packer to implement js
gem 'webpacker', '~> 3.5', '>= 3.5.5'

# petersgame for authorization
gem 'petergate', '~> 2.0', '>= 2.0.1'

# notification game
gem 'gritter', '~> 1.2'

# font awesome rails icons for ex. facebook github
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.4'

# kaminari gem for pagination
gem 'kaminari', '~> 1.1', '>= 1.1.1'

# image gems
gem 'carrierwave', '~> 1.3', '>= 1.3.1'
gem 'mini_magick', '~> 4.9', '>= 4.9.2'
gem 'carrierwave-aws', '~> 1.3'
gem 'dotenv-rails', '~> 2.1', '>= 2.1.1'

# twitter gem
gem 'twitter', '~> 6.2'
gem 'dotenv', '~> 2.6'

# like database not based on sql. fast and easy
gem 'redis', '~> 4.1'

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'pry-byebug'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
