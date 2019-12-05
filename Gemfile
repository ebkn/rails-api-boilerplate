source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

gem 'rails', '~> 5.2.2'

gem 'mysql2', '>= 0.4.4', '< 0.6.0'
# web server
gem 'puma', '~> 3.12'
# cache for server
gem 'bootsnap', '>= 1.1.0', require: false
# manage secrets
gem 'dotenv-rails'

group :development, :test do
  # debug
  gem 'pry-rails'
  gem 'pry-byebug'
  # test
  gem 'rspec-rails'
  gem 'factory_bot_rails'
  gem 'simplecov'
  # check query
  gem 'bullet'
  # linter
  gem 'rubocop', require: false
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring-watcher-listen', '~> 2.0.0'
  # debug
  gem 'better_errors'
  # annotation
  gem 'annotate'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
