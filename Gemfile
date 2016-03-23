source 'https://rubygems.org'

gem 'rails', '~> 4.2.5'

gem 'pg'

gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc

group :development do
  gem 'web-console', '~> 3.1'
  gem 'spring', platform: :ruby
  gem "dotenv-rails"
end

gem 'figaro'
gem 'rename'

# wechat related
gem 'wechat'
gem 'omniauth-wechat-oauth2'

# account system
gem 'devise'
# style
gem 'weui-rails'
# server
gem 'puma'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin]

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'pry', '~> 0.10.3'
  gem 'byebug'
  gem 'rspec-rails'
  gem 'shoulda-matchers', require: false
  gem 'pry-rails'
  gem 'awesome_print'
  gem 'database_cleaner', '~> 1.5.1'
  gem 'ffaker'
  gem 'factory_girl', '~> 4.5.0'
  gem 'brakeman', require: false
end

group :test do
  gem "timecop"
  gem 'capybara', '~> 2.6.0'
  gem 'capybara-webkit', '~> 1.8', '>= 1.8.0'
  gem 'webmock', '~> 1.24.1'
  gem 'rspec-activemodel-mocks'
  gem 'sqlite3'
end

gem 'redis'
