ruby File.read(".ruby-version").strip

source "https://rubygems.org"

gem "rails", "4.2.6"
gem "unicorn", "~> 5.1.0"
gem "logstasher", "0.6.2"
gem "database_cleaner"
gem "deprecated_columns"
gem "gds-sso", "12.1.0"
gem "plek", "~> 1.12"
gem "airbrake", "~> 5.4.1"
gem "selectize-rails", "~> 0.12"
gem "generic_form_builder", "~> 0.13"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"
gem "quiet_assets", "1.1.0"
gem "govuk_admin_template", "~> 3.5"
group :development, :test do
  gem "pry"
  gem "simplecov-rcov", "0.2.3", require: false
  gem "simplecov", "0.11.2", require: false
  gem "govuk-lint"
  gem "sqlite3" # Remove this when you choose a production database
  gem "factory_girl_rails", "4.7.0"
  gem "timecop"
  gem "webmock", require: false
  gem "rspec-rails", "~> 3.4"
  gem "byebug" # Comes standard with Rails
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem "web-console", "~> 2.0"
end
