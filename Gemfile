source 'https://rubygems.org'

gem 'sinatra', '~> 2.2', '>= 2.2.3'
gem 'sinatra-contrib', '~> 2.2', '>= 2.2.3'
gem 'nokogiri', '~> 1.13', '>= 1.13.9'
gem 'mongo', '~> 2.1.2'
gem 'puma', '~> 4.3.12'

group :production do
  gem 'capistrano', '~> 3.9.0'
  gem 'capistrano-bundler', '~> 1.2.0'
  gem 'capistrano-rvm', '~> 0.1.2'
  gem 'capistrano3-puma', '~> 4.0.0'
end

group :development, :test do
  gem 'pry', '~> 0.10.4'
  gem 'rspec', '~> 3.6.0'
  gem 'rack-test', '~> 2.0', '>= 2.0.0'
  gem 'simplecov', '~> 0.15.0', :require => false
end
