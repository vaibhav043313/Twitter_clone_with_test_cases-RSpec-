source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.3'

gem 'rails', '~> 6.1.4', '>= 6.1.4.1'
gem 'puma', '~> 5.0'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'
gem 'faker', '~> 2.19'
gem 'carrierwave', '~> 2.2', '>= 2.2.2'
gem 'mini_magick', '~> 4.11'
# gem 'fog', '~> 2.2'
gem 'will_paginate', '~> 3.3', '>= 3.3.1'
gem 'uglifier', '~> 4.2'
gem 'coffee-rails', '~> 5.0'
gem 'jquery-rails', '~> 4.4'
gem 'sdoc', '~> 2.2'
gem 'bootstrap-sass', '~> 3.4', '>= 3.4.1'
#gem 'bootstrap', '~> 5.1', '>= 5.1.3'

# gem 'redis', '~> 4.0'
gem 'bcrypt', '~> 3.1.7'

# gem 'image_processing', '~> 1.2'

gem 'bootsnap', '>= 1.4.4', require: false

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 4.1.0'
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'listen', '~> 3.3'
  gem 'spring'
  gem 'sqlite3', '~> 1.4'
end

group :test do
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver'
  gem 'webdrivers'
  gem 'minitest-reporters', '1.0.5'
  gem 'mini_backtrace',     '0.1.3'
  gem 'guard-minitest',     '2.3.1'
  gem 'rails-controller-testing', '~> 1.0', '>= 1.0.5'
end

group :production do
  gem 'pg',             '0.17.1'
  gem 'rails_12factor', '0.0.2'
end
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]