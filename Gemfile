source "https://rubygems.org"

ruby "2.7.0"

gem 'sinatra', '~> 2.0'
gem 'sinatra-flash', '~> 0.3'
gem 'dotenv', '~> 2.7'
gem 'rake', '~> 13.0'
gem 'sequel', '~> 5.25'
gem 'sidekiq', '~> 6.0'

group :development, :test do
  gem 'sqlite3', '~> 1.4'
end

group :production do
  gem 'pg', '~> 1.1'
end
