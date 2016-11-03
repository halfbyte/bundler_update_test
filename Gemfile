source "http://rubygems.org"

gem "rails", "4.2.7.1"

gem 'sass-rails', '~> 5.0.6'
gem 'compass-rails', '~> 3.0'
gem 'susy'
gem 'coffee-rails', '~> 4.0'
gem 'uglifier', '>= 1.0.3'

gem "mysql2", "~> 0.4"

gem 'uuidtools'
gem 'mini_magick', '~> 4.5'
gem 'haml-contrib'
gem 'haml-rails', '~> 0.9'
gem 'json'

gem 'protected_attributes'

gem 'unicorn'
gem "sentry-raven"

gem 'redis-rails', '~> 4.0'
gem 'redis-namespace'

# TODO: remove version requirement on r3 upgrade
gem 'acts_as_list', '~> 0.8'

gem 'rails_autolink'

gem 'mimetype-fu', :require => 'mimetype_fu'
gem 'country_select', '~> 2.5'

gem 'carrierwave', '~> 0.11'
gem 'fog', "~> 1.3"

gem 'recaptcha', "~> 3.3", :require => 'recaptcha/rails'

gem 'will_paginate'

gem 'acts-as-taggable-on', '~> 4.0'

gem 'permit_yo', :git => 'https://github.com/halfbyte/permityo.git', branch: 'rails_4'

gem 'prototype-rails', git: 'https://github.com/rails/prototype-rails', branch: '4.2'

gem 'jquery-rails'
gem "calendar_helper", :git => "https://github.com/topfunky/calendar_helper.git"

# gem 'authorization', :git => 'git://github.com/g5search/rails-authorization-plugin.git', :require => 'authorization'

# comatose deps
gem "RedCloth", :require => 'redcloth'
gem "liquid"

gem 'rdoc'

gem 'newrelic_rpm'

gem 'faraday'

gem 'sidekiq', '~> 4.1'
# gem 'xapian_db' # , :git => "git://github.com/halfbyte/xapian_db.git", :branch => 'fixing_total_pages'
# gem 'xapian-ruby'

gem 'lograge'

gem 'slack-poster'

gem 'sinatra', :require => false # for sidekiq admin

gem 'dusen', git: 'https://github.com/halfbyte/dusen'

group :development do
  gem 'capistrano'
  gem 'capistrano-ext'
  gem 'capistrano-unicorn', :require => false
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'
  gem 'web-console', '~> 2.0'
  gem 'byebug'
  gem 'minitest-byebug'
  gem 'gemsurance'
  gem 'spring'
end

group :test do
  gem "mocha", require: false
  gem "capybara"
  gem "poltergeist"
  gem "database_cleaner"
  gem "capybara-screenshot"
  gem 'rails-perftest'
  gem 'ruby-prof', '~> 0.15.8'
end
