source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }
ruby "3.0.0"
gem "rails", "~> 7.0.5"
gem "sprockets-rails"
gem "sqlite3", "~> 1.4"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false

# My Custome Gems
gem 'devise', '~> 4.9', '>= 4.9.4'

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end
group :development do
  gem "web-console"

end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

gem "dockerfile-rails", ">= 1.6", :group => :development

gem "pg", "~> 1.5"
