# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gemspec

gem "rails", "~> 5.2.8"
gem "rack"

group :development do
  platform :ruby do
    gem "byebug"
  end
  gem "puma"
end

group :test do
  gem "rake"
  gem "mocha", require: false
  gem "simplecov", require: false
end
