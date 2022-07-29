source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"
gem "bootsnap", require: false
gem "importmap-rails"
gem "jbuilder"
gem "puma", "~> 5.0"
gem "rails", "~> 7.0.3", ">= 7.0.3.1"
gem "sprockets-rails"

gem "stimulus-rails"
gem "turbo-rails"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

gem 'devise', '~> 4.8', '>= 4.8.1'
gem 'ordinare', '~> 0.4.0'
gem 'rodauth', '~> 2.25'


group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "sqlite3", "~> 1.4"
end

group :development do
  gem "web-console"
end

group :production do
  gem 'pg', '~> 1.4', '>= 1.4.2'
  # gem 'rails_12factor', '0.0.2'
end
group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
