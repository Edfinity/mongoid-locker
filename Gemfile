source 'http://rubygems.org'

gem 'mongoid', '>= 2.4', '<= 4'


# groups need to be copied to gemfiles/*.gemfile

group :development do
  gem 'rspec', '~> 2.8'
  gem 'bundler', '~> 1.1'
  gem 'jeweler', '~> 1.8'

  gem 'guard-rspec'
  gem 'rb-fsevent', '~> 0.9.1'
end

group :development, :test do
  gem 'bson_ext', :platforms => :ruby

  gem 'rake'
  gem 'appraisal', git: 'git@github.com:thoughtbot/appraisal.git', ref: '55e158f894d4240c6e7d972b3af611f2f8bde26d'
end
