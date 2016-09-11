source 'https://rubygems.org'

# PostgreSQL driver
gem 'pg'

# Sinatra driver
gem 'sinatra'
gem 'sinatra-contrib'

gem 'activesupport', '~>4.2.0'
gem 'activerecord', '~>4.2.0'

gem 'rake'
gem 'dotenv'
gem 'shotgun'
gem 'pry'

group :test do
  gem 'shoulda-matchers'
  gem 'rack-test'
  gem 'capybara'
  gem 'database_cleaner', '~> 1.4.1'
  gem 'irbtools', require: 'irbtools/binding'
end

group :test, :development do
  gem 'factory_girl'
  gem 'faker'
  gem 'rspec', '~>3.0'
end
