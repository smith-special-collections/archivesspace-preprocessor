source 'https://rubygems.org'
ruby '2.2.2', :engine => 'jruby', :engine_version => '9.0.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.4'
# Use jdbcpostgresql as the database for Active Record
gem 'activerecord-jdbcpostgresql-adapter'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyrhino'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# jqPlot-Rails - least outdated package
gem 'outfielding-jqplot-rails', '~> 1.0.0'
gem 'dotenv-rails'

group :development do
  gem 'puma' # Because Webrick is terrible 
  gem 'capistrano-rails', '~> 1.1'
  gem 'capistrano-rvm'
  gem 'capistrano-passenger'
end

group :doc do
  gem 'yard', '~> 0.8.7'
  gem 'yard-activerecord'
  gem 'kramdown'
end

group :test do
  gem 'capybara'
  gem 'poltergeist'
  gem 'poltergeist-suppressor'
  gem 'minitest-capybara'
  gem 'minitest-spec-rails'
  gem 'minitest-metadata'
  gem 'database_cleaner'
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

gem 'railroady', group: :development

gem 'pry-rails'
gem 'pry-nav'
gem 'pry-remote'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'schematronium'
