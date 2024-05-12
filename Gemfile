source "https://rubygems.org"

ruby "3.2.1"
gem "rails", "~> 7.1.3", ">= 7.1.3.2"
gem "image_processing"
gem "active_storage_validations"
gem "bootstrap-sass", "3.4.1"
gem "sassc-rails"
gem "sprockets-rails"
gem "importmap-rails"
gem "sqlite3", "~> 1.4"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bcrypt", "3.1.18"
gem "faker"
gem "will_paginate"
gem "will_paginate-bootstrap-style"

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri windows ]
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"
  gem "solargraph"
  gem "irb"
  gem "repl_type_completor"
  # gem "spring"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
  gem "rails-controller-testing"
  gem "minitest"
  gem "minitest-reporters"
  gem "guard"
  gem "guard-minitest"
end

group :production do
  gem "pg", "1.3.5"
end
