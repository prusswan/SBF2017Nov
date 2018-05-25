source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.1'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '>= 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development


gem 'sbf', github: 'prusswan/sbf' #, branch: 'engine-migrations'
# gem 'sbf', path: '~/Projects/sbf'

gem 'settingslogic'
gem 'activesupport-decorators', '~> 1.0'
gem 'render_csv'

group :development, :test do
  gem 'byebug'
  gem 'rspec-rails', '~> 3.5'
  gem 'capybara'
  gem 'poltergeist'
  gem 'capybara-webkit'
  gem 'capybara-selenium'
  gem 'chromedriver-helper'

  gem 'mysql2', '~> 0.5.0'

  # gem 'protected_attributes'

  # for pushing db seed to heroku
  # gem 'heroku', '~> 2.40'
  gem 'taps'
  gem 'sqlite3'
end

group :development do
  gem 'seed_dump'
  gem 'web-console', '~> 2.0'
  # gem 'quiet_assets' # not need for Rails 5
end

group :production do
  gem 'rails_12factor'
  gem 'pg'
end
