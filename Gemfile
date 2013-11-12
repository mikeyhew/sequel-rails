source 'https://rubygems.org'

gemspec

gem 'actionpack'
gem 'fakefs', :require => 'fakefs/safe'
gem 'pry'

# MRI/Rubinius Adapter Dependencies
platform :ruby do
  gem 'pg'
  gem 'mysql'
  gem 'mysql2'
  gem 'sqlite3'
end

# JRuby Adapter Dependencies
platform :jruby do
  gem 'jdbc-sqlite3'
  gem 'jdbc-mysql'
  gem 'jdbc-postgres'
end
