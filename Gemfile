source "https://rubygems.org"

# Application
gem "rake"
gem "rails", "4.0.0"
gem "rest-client", "~> 1.6.7"
gem "yajl-ruby", "~> 1.1.0"

# Assets
gem "jquery-rails"
gem "sass-rails"
gem "haml-rails"
gem "coffee-rails"
gem "bootstrap-sass", "~> 2.3.2.0"
gem "uglifier"

group :development, :test do
  gem "rspec-rails"
  gem "cucumber-rails", :require => false
  gem "vcr", "~> 2.5.0"
  gem "webmock", "~> 1.11.0"
  gem "pry"
  gem "pry-byebug"
  gem "pry-remote"
  gem "pry-rescue"
  gem "pry-stack_explorer"
  gem "pry-vterm_aliases"
  gem "pry-git"
  gem "pry-doc"
  gem "jasmine-rails"
  gem "sinon-rails"
  gem "coffee-rails-source-maps", "~> 1.3.6"
end

group :production do
  gem "therubyracer"
  gem "thin", "~> 1.5.1"
end

group :development do
  gem "quiet_assets"
  gem "guard"
  gem "guard-bundler"
  gem "guard-coffeescript"
  gem "guard-cucumber"
  gem "guard-jasmine"
  gem "guard-rspec"
  gem "rb-fsevent", "~> 0.9"
  gem "capistrano", "2.15.4"
  gem "capistrano-ext", "1.2.1"
end