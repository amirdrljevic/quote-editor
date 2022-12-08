source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.1"
gem "rails", "~> 7.0.3", ">= 7.0.3.1"
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "turbo-rails", "~> 1.0"
gem "puma", "~> 5.0"
gem "stimulus-rails"
gem "cssbundling-rails", "~> 0.1.0"
gem "jbuilder"
gem "jsbundling-rails", "~> 0.1.0"
gem "simple_form", "~> 5.1.0"
gem 'sass-rails', '~> 6.0'

gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

gem "bootsnap", require: false

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

# Use Redis for Action Cable
gem 'redis-rails', '~> 5.0', '>= 5.0.2'
gem "redis", "~> 4.0"
