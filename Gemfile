source 'https://rubygems.org'
# Ruby version
ruby '2.3.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '5.0.0.1'
# Use mysql as the database for Active Record
gem 'mysql2', '0.4.4'

# Use Puma as the app server
# gem 'puma', '~> 3.0'

# Use SCSS for stylesheets
gem 'sass-rails', '5.0.6'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '3.0.2'

# Use CoffeeScript for .coffee assets and views
# gem 'coffee-rails', '4.2.1'

# Use jquery as the JavaScript library
# gem 'jquery-rails', '4.2.1'

# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '2.6.0'

# Use Unicorn as the app server
gem 'unicorn'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '3.1.11'

# XML/HTML parsar
# gem 'nokogiri', '1.6.8'

# multilingualize library
gem 'rails-i18n', '5.0.1'

# for Only Development Environment
group :development do
end

# for Development/Staging Environment
group :test do
end

group :development, :test do
  # pre-loader
  gem 'spring', '2.0.0'
  # RSpec
  gem 'rspec-rails', '3.5.0'
  # For connect the spring and RSpec
  gem 'spring-commands-rspec', '1.0.4'
  # For End to End Plugin
  gem 'capybara', '2.9.2'
  # Selenium
  gem 'selenium-webdriver', '2.53.4'
  # For input test data
  gem 'factory_girl_rails', '4.7.0'
end

# for Only Production Environment
group :production do
end