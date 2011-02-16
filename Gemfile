source 'http://rubygems.org/'

gem 'rails',      '= 2.3.5'
gem 'haml',       '~> 2.2.3'
gem 'compass',    '~> 0.8.0'
gem 'formtastic', '~> 0.9.8'
gem 'authlogic'

# NOTE: using fork of the thoughtbot gem for :database storage module
# and then a fork of that which adds our changes for ImageMagick compat
gem 'paperclip', '~> 2.3.0', :git => 'http://github.com/cbrunnkvist/paperclip.git'


# These two are only needed in the deployed environments, and in test
gem 'mysql'
gem 'net-ldap'

gem "cbrunnkvist-psd_logger"

group :development do
  gem 'sqlite3-ruby',     '~> 1.2.0', :require => 'sqlite3'
end

group :test do
  gem 'test-unit',    '~> 1.2.3'
  gem 'rspec-rails',  '~> 1.3.2'
  gem 'nokogiri'
  gem 'webrat'
  gem 'ci_reporter'
end

group :cucumber do
#  gem "capybara", '~>0.3.9', :require => false
  gem "cucumber-rails"
  gem "database_cleaner", :require => false
  gem "factory_girl", '~>1.3.1'
end

group :deployment do
  gem 'thin'
end
