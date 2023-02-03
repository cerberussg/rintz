# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.0"

gem "bootsnap", require: false
gem "cancancan"
gem "devise"
gem "devise_invitable"
gem "gravatar_image_tag"
gem "immutable-struct"
gem "importmap-rails"
gem "jbuilder"
gem "local_time"
gem "money-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "rack-cors", require: "rack/cors"
gem "rails", "~> 7.0.4", ">= 7.0.4.2"
gem "redis", "~> 4.0"
gem "rolify"
gem "sidekiq"
gem "sinatra", require: nil
gem "slack-notifier"
gem "sprockets-rails"
gem "stimulus-rails"
gem "tailwindcss-rails", "~> 2.0"
gem "turbo-rails"
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  gem "capybara"
  gem "debug", platforms: %i[mri mingw x64_mingw]
  gem "dotenv-rails"
  gem "factory_bot_rails"
  gem "rails-controller-testing"
  gem "rspec-rails"
  gem "simplecov", require: false, group: :test
end

group :development do
  gem "foreman"
  gem "letter_opener"
  gem "web-console"
end
