source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

gem 'bcrypt'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'carrierwave'
gem 'fast_jsonapi'
gem 'ffaker'
gem 'jwt'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'rack-cors'
gem 'rails', '~> 5.2.3'

group :development, :test do
  gem 'pry-rails'
end

group :test do
  gem 'database_cleaner'
  gem 'factory_bot_rails'
  gem 'json-schema'
  gem 'rails-controller-testing'
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'rubocop'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
