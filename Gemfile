source "https://rubygems.org"

ruby "3.0.0"

gem "rails", "~> 7.1.3", ">= 7.1.3.2"
gem 'mysql2', '>= 0.5.6'
gem "puma", ">= 5.0"
gem 'jwt'
gem 'bcrypt', '~> 3.1.7'
gem "tzinfo-data", platforms: %i[ mswin mswin64 mingw x64_mingw jruby ]
gem "bootsnap", require: false
gem 'jbuilder'
gem 'rack-cors'
gem 'sidekiq'

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mswin mswin64 mingw x64_mingw ]
  gem 'ffaker'
  gem 'rspec-rails'
  gem 'factory_bot_rails'
  gem 'shoulda-matchers'
  gem 'rails-controller-testing'
end

group :development do
  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

