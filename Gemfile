source 'https://rubygems.org'
# Ruby version
ruby '2.3.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '5.0.0.1'
# Use mysql as the database for Active Record
# ドライバ
gem 'mysql2', '0.4.4'

# Use Puma as the app server
# uniconを使うのでコメントアウト
# gem 'puma', '~> 3.0'

# Use SCSS for stylesheets
# スタイルシート言語なので入れておく
gem 'sass-rails', '5.0.6'

# Use Uglifier as compressor for JavaScript assets
# JavaScript のコード軽量化ライブラリなので、そのうち必要になるため入れる
gem 'uglifier', '3.0.2'

# Use CoffeeScript for .coffee assets and views
# ひとまず使わないためにコメントアウト
# gem 'coffee-rails', '4.2.1'

# Use jquery as the JavaScript library
# ひとまず使わないためにコメントアウト
# gem 'jquery-rails', '4.2.1'

# See https://github.com/rails/execjs#readme for more supported runtimes
# v8 javascritp のインタープリター Linux上でrailsを動かすために必要なので入れる
gem 'therubyracer', platforms: :ruby

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# JSONライブラリ
gem 'jbuilder', '2.6.0'

# bundle exec rake doc:rails generates the API under doc/api.
# 動作に害はないので入れる
gem 'sdoc', '0.4.1', group: :doc

# Use Unicorn as the app server
gem 'unicorn'

# Railsのプリローダライブラリ
# 開発中の起動時間の短縮が見込まれるので入れる
gem 'spring', '2.0.0', group: :development

# Use ActiveModel has_secure_password
# 暗号化ライブラリ
# gem 'bcrypt', '3.1.11'

# XML/HTMLパーサ
# 必要ないと思われるためコメントアウト
# gem 'nokogiri', '1.6.8'

# railsが出力するメッセージの多言語ライブラリ
# 使うフローはありそうなので、入れる
gem 'rails-i18n', '5.0.1'

group :test do
  # RSpec
  gem 'rspec-rails', '3.5.0'
  # SpringとRSpecの連携
  gem 'spring-commands-rspec', '1.0.4'
  # HTTPのモックライブラリ
  gem 'capybara', '2.9.2'
  # Selenium
  gem 'selenium-webdriver', '2.53.4'
  # DBへのデータ投入用ライブラリ
  gem 'factory_girl_rails', '4.7.0'
end