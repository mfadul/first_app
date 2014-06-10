source 'https://rubygems.org'

gem 'rails', '3.2.13'

# for deployment on Heroku
gem "heroku"
group :development, :test do
  gem 'sqlite3'
end
group :production do
  gem 'pg'
  gem 'thin'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.4'
  gem 'uglifier', '>= 1.3.3'
end

gem 'jquery-rails'