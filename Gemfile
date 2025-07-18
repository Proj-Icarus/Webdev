source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.4.4'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 8.0', '>= 8.0.2'
# Use Puma as the app server
gem 'puma', '~> 6.6'
# Use SCSS for stylesheets
gem 'dartsass-rails', '~> 0.5.1'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 5.4', '>= 5.4.4'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5', '~> 5.2', '>= 5.2.1'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.13'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

gem 'devise', '~> 4.9', '>= 4.9.4'
gem 'turbo-rails', '~> 2.0', '>= 2.0.16'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '~> 1.18', '>= 1.18.6', require: false

gem 'sprockets', '~> 4.2', '>= 4.2.2'
gem 'sprockets-rails', '~> 3.5', '>= 3.5.2'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '~> 4.2', '>= 4.2.1'
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3', git: "https://github.com/sparklemotion/sqlite3-ruby"
  gem "capistrano", "~> 3.10"
  gem 'capistrano-bundler', '~> 2.0'
  gem "capistrano-rails", "~> 1.3"
end

group :production do
  gem 'pg', '~> 1.5', '>= 1.5.9'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 3.40'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem "concurrent-ruby", '~> 1.3', '>= 1.3.5'

gem "minitest", '~> 5.25', '>= 5.25.5'
