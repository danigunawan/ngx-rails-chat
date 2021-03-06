source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.2'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :development, :test do
  gem 'rails-erd'
  gem 'rspec-rails', '~> 3.5'
  gem 'rails-controller-testing'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'guard-rspec', require: false
  gem 'byebug', platform: :mri
end

group :development do
  # gem 'lx', git: 'git@git.pixelfaucet.com:alex/lxgen.git'
  gem 'capistrano'
  gem 'capistrano-rails'
  gem 'capistrano-rails-db'
  gem 'capistrano-rvm'
  gem 'capistrano-bundler'
  gem 'capistrano-passenger'
  gem 'capistrano-touch-linked-files'
  gem 'capistrano-rails-console', require: false
  gem 'scss_lint'
  gem 'annotate'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'jwt'
gem 'dotenv-rails'
gem 'wirble'
gem 'awesome_print'
gem 'hirb'
gem 'rack-rewrite'
