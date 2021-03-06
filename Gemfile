source 'https://rubygems.org'
ruby '2.3.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.6'
gem 'mysql2', '>= 0.3.13', '< 0.5'
gem 'sass-rails', '~> 5.0'
gem 'font-awesome-sass', '~> 4.4.0'
gem 'twilio-ruby'

gem 'puma'

gem 'materialize-sass'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
# gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
gem 'jquery_mobile_rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

gem 'devise'
gem 'will_paginate'

gem 'rails-i18n'
gem 'devise-i18n'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development


group :test do
  gem 'shoulda-matchers', '~> 3.0'
  gem 'factory_girl_rails'
  gem 'mocha'
  gem 'capybara'
  gem 'launchy'
  gem 'webmock'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'spring'
  gem 'rspec-rails', '~> 3.0'
  gem 'spring-commands-rspec'
  gem 'bullet'
  gem 'dotenv-rails'
end

group :development do
  gem 'guard-rspec', require: false
  gem 'foreman'
  gem 'web-console', '~> 2.0'
  gem 'guard-livereload', '~> 2.4', require: false
end

group :production do
  gem 'rails_12factor'
end
