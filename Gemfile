source 'http://rubygems.org'
gemspec

group :development do
  gem 'rails', :git => 'git://github.com/rails/rails.git', :branch => '4-0-stable'
  # https://github.com/rails/rails/issues/6039
  gem 'activerecord-deprecated_finders', git: 'https://github.com/tesserakt/activerecord-deprecated_finders.git'
  platforms :jruby do
    gem 'jdbc-sqlite3', :require => false
  end
  platforms :ruby do
    gem 'sqlite3-ruby', :require => 'sqlite3'
  end
  gem 'pry'
end
