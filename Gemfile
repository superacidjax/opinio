source "http://rubygems.org"

gemspec

gem "kaminari"
gem "rails"
gem "sqlite3"
gem "jquery-rails"
gem 'protected_attributes'

group :development do
  platforms :mri_19 do
    gem "debugger"
  end
  gem 'guard-rspec'
  if RUBY_PLATFORM =~ /darwin/i
    gem 'rb-fsevent'
    gem 'growl'
  end
end

group :test do
  gem "cucumber"
  gem "cucumber-rails"
  gem "capybara"
  gem "launchy"
  gem "database_cleaner"
  gem "rspec-rails"
end