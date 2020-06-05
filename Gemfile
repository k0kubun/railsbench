source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rails'
gem 'pg', platforms: [:mri, :truffleruby]
gem 'activerecord-jdbcpostgresql-adapter', platforms: [:jruby]
gem 'puma'
gem 'sass-rails'
gem 'uglifier'

gem 'coffee-rails'
gem 'turbolinks'
gem 'jbuilder'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console'
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'stackprof', platforms: [:mri]
