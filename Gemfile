source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.2'

# Full-stack web application framework. (https://rubyonrails.org)
gem 'rails', '~> 7.0.3'

# Sprockets Rails integration (https://github.com/rails/sprockets-rails)
gem 'sprockets-rails'

# Adds multiple exporters to Sprockets (https://github.com/hansottowirtz/sprockets-exporters_pack)
gem 'sprockets-exporters_pack'

# The speed of a single-page web application without having to write any JavaScript. (https://github.com/hotwired/turbo-rails)
gem 'turbo-rails'

# A modest JavaScript framework for the HTML you already have. (https://stimulus.hotwired.dev)
gem 'stimulus-rails'

# Bundle and transpile JavaScript in Rails with esbuild, rollup.js, or Webpack. (https://github.com/rails/jsbundling-rails)
gem 'jsbundling-rails'

# Bundle and process CSS with Tailwind, Bootstrap, PostCSS, Sass in Rails via Node.js. (https://github.com/rails/cssbundling-rails)
gem 'cssbundling-rails'

# View components for Rails (https://github.com/github/view_component)
gem 'view_component'

# Slim templates generator for Rails (https://github.com/slim-template/slim-rails)
gem 'slim-rails'

# Rails View Helpers for Heroicons. (https://github.com/bharget/heroicon)
gem 'heroicon'

# Pg is the Ruby interface to the PostgreSQL RDBMS (https://github.com/ged/ruby-pg)
gem 'pg', '~> 1.1'

# Puma is a simple, fast, threaded, and highly parallel HTTP 1.1 server for Ruby/Rack applications (https://puma.io)
gem 'puma', '~> 5.0'

# Boot large ruby/rails apps faster (https://github.com/Shopify/bootsnap)
gem 'bootsnap', '>= 1.4.4', require: false

# Timezone Data for TZInfo (https://tzinfo.github.io)
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# A Ruby client library for Redis (https://github.com/redis/redis-rb)
gem 'redis'

# Error reports you can be happy about. (https://github.com/honeybadger-io/honeybadger-ruby)
gem 'honeybadger'

# Tame Rails' multi-line logging into a single line per request (https://github.com/roidrage/lograge)
gem 'lograge'

# Middleware for enabling Cross-Origin Resource Sharing in Rack apps (https://github.com/cyu/rack-cors)
gem 'rack-cors', require: 'rack/cors'

# Rack middleware for defining a canonical host name. (https://github.com/tylerhunt/rack-canonical-host)
gem 'rack-canonical-host'

# Brotli compression for Rack responses (http://github.com/marcotc/rack-brotli/)
gem 'rack-brotli'

# Simple, efficient background processing for Ruby (https://sidekiq.org)
gem 'sidekiq'

# Lock staging servers from search engines and prying eyes. (http://lockup.interdiscipline.com)
gem 'lockup'

group :development, :test do
  # Debugging functionality for Ruby (https://github.com/ruby/debug)
  gem 'debug', '>= 1.0.0', platforms: %i[mri mingw x64_mingw]

  # Autoload dotenv in Rails. (https://github.com/bkeepers/dotenv)
  gem 'dotenv-rails'

  # RSpec for Rails (https://github.com/rspec/rspec-rails)
  gem 'rspec-rails'

  # factory_bot_rails provides integration between factory_bot and rails 5.0 or newer (https://github.com/thoughtbot/factory_bot_rails)
  gem 'factory_bot_rails'

  # Automatic Ruby code style checking tool. (https://github.com/rubocop/rubocop)
  gem 'rubocop', require: false

  # Automatic performance checking tool for Ruby code. (https://github.com/rubocop/rubocop-performance)
  gem 'rubocop-performance', require: false

  # Automatic Rails code style checking tool. (https://github.com/rubocop/rubocop-rails)
  gem 'rubocop-rails', require: false

  # Code style checking for RSpec files (https://github.com/rubocop/rubocop-rspec)
  gem 'rubocop-rspec', require: false

  # Slim template linting tool (https://github.com/sds/slim-lint)
  gem 'slim_lint'
end

group :development do
  # A debugging tool for your Ruby on Rails applications. (https://github.com/rails/web-console)
  gem 'web-console', '>= 4.1.0'

  # Profiles loading speed for rack applications. (https://miniprofiler.com)
  # gem 'rack-mini-profiler', '~> 2.0'

  # Listen to file modifications (https://github.com/guard/listen)
  gem 'listen', '~> 3.3'

  # Guard gem for RSpec (https://github.com/guard/guard-rspec)
  gem 'guard-rspec', require: false

  # Rails application preloader (https://github.com/rails/spring)
  gem 'spring'

  # rspec command for spring (https://github.com/jonleighton/spring-commands-rspec)
  gem 'spring-commands-rspec'

  # A native development UI for ViewComponent (https://github.com/allmarkedup/lookbook)
  gem 'lookbook'
end

group :test do
  # Code coverage for Ruby (https://github.com/simplecov-ruby/simplecov)
  gem 'simplecov', require: false

  # Capybara aims to simplify the process of integration testing Rack applications, such as Rails, Sinatra or Merb (https://github.com/teamcapybara/capybara)
  gem 'capybara'
end
