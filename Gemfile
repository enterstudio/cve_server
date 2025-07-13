source 'https://rubygems.org'

gem 'sinatra', '~> 2.0', '>= 2.0.1'
gem 'sinatra-contrib', '~> 2.0', '>= 2.0.1'
gem 'nokogiri', '~> 1.8'
gem 'mongo', '~> 2.1.2'
gem 'puma', '~> 3.10.0'

group :production do
  gem 'capistrano', '~> 3.9.1'
  gem 'capistrano-bundler', '~> 1.3.0'
  gem 'capistrano-rvm', '~> 0.1.2'
  gem 'capistrano3-puma', '~> 5.0.0'
end

group :development, :test do
  gem 'pry', '~> 0.10.4'
  gem 'rspec', '~> 3.6.0'
  gem 'rack-test', '~> 2.0', '>= 2.0.0'
  gem 'simplecov', '~> 0.15.0', :require => false
end
