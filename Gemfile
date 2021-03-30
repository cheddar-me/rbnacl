# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "ffi", github: "cheddar-me/ffi", branch: "apple-m1", submodules: true

group :development do
  gem "guard-rspec"
end

group :test do
  gem "coveralls", require: false
  gem "rspec"
  gem "rubocop", "= 0.70.0"
end

group :development, :test do
  gem "rake"
end
