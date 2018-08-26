source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

gem 'rails', '~> 5.2.1'

gem 'mysql2', '>= 0.4.4', '< 0.6.0'
# web server
gem 'puma', '~> 3.11'
# cache for server
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  # debug
  gem 'pry-rails'
  gem 'pry-byebug'
  # test
  gem 'rspec-rails'
  gem 'factory_bot_rails'
  gem 'simplecov'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'better_errors'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
