# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github){|repo| "https://github.com/#{repo}.git"}

ruby "3.0.1"

gem "bootsnap", ">= 1.4.4", require: false
gem "jbuilder", "~> 2.7"
gem "puma", "~> 5.0"
gem "rails", "~> 6.1.6"
gem "sass-rails", ">= 6"
gem "turbolinks", "~> 5"
gem "webpacker", "~> 5.0"

group :development do
  gem "listen", "~> 3.3"
  gem "rack-mini-profiler", "~> 2.0"
  gem "spring"
  gem "web-console", ">= 4.1.0"
end

gem "bson_ext"
gem "mongoid", "~> 7.4.0"

group :development, :test do
  gem "pry-rails"
  gem "rubocop", "~> 1.26", require: false
  gem "rubocop-checkstyle_formatter", require: false
  gem "rubocop-rails", "~> 2.14.0", require: false
end

gem "tzinfo-data", platforms: %i(mingw mswin x64_mingw jruby)
