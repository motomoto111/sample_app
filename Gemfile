source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.3.4"

gem "rails", "~> 7.0.8", ">= 7.0.8.4"
gem "sprockets-rails", "3.4.2"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false
gem "bootstrap-sass", "3.4.1"
gem "sassc-rails", "2.1.2"
gem 'rails-controller-testing'
gem "bcrypt", "3.1.18"
gem "faker", "2.21.0"
gem "will_paginate", "3.3.1"
gem "bootstrap-will_paginate", "1.0.0"
gem 'hirb'
gem "active_storage_validations", "0.9.8"
gem "image_processing",           "1.12.2"
gem 'pg', '~> 1.1'
gem 'mutex_m'
gem 'base64'
gem 'bigdecimal'
gem 'drb'


group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"
  gem 'letter_opener'
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end

group :production do
  gem "aws-sdk-s3", "1.114.0", require: false
end
