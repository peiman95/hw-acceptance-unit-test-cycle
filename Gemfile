source 'https://rubygems.org'

ruby '>= 2.4.0', '< 2.6'
gem 'rails', '4.2.10'

# for Heroku deployment - as described in Ap. A of ELLS book
group :development, :test do
  gem 'sqlite3'
  gem 'byebug'
  gem 'database_cleaner', '1.4.1'
  gem 'capybara', '2.4.4'
  gem 'launchy'
  gem 'rspec-rails', '3.7.2'
  gem 'ZenTest', '4.12.0'
  #gem 'factory_girl_rails'
  gem 'factory_bot_rails'
end

group :test do
  gem 'cucumber-rails', :require => false
  gem 'cucumber-rails-training-wheels'
  gem 'simplecov', :require => false
  gem 'factory_bot_rails'
end
group :production do
  #gem 'pg'
  gem 'pg', '~> 0.20'
end

# Gems used only for assets and not required
# in production environments by default.

gem 'sass-rails', '~> 5.0.3'
gem 'coffee-rails', '~> 4.1.0'
gem 'uglifier', '>= 2.7.1'
gem 'jquery-rails'
gem 'haml'
