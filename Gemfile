source 'https://rubygems.org'

gemspec

group :development do
  # Integration testing gems.
  gem 'kitchen-inspec', '~> 2.0'
  gem 'inspec', '>= 4.26.2'
  gem 'train', '>= 2.1', '< 4.0' # validate 4.x when it's released
  # Silence ruby 3.4.0 standard gem deprecation warnings
  gem 'csv', '~> 3.3.0'
  gem 'syslog', '~> 0.1.1'
end

group :test do
  gem 'bundler'
  gem 'rake'
  gem 'rspec', '~> 3.2'
  gem 'rspec-its', '~> 1.2'
end

group :chefstyle do
  gem 'chefstyle', '~> 2.2', '>= 2.2.3'
end
