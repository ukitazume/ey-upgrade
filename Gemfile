source 'https://rubygems.org'


gem 'bundler', '~> 1.12.5'
# putting this first so we have pry available when loading other gems
group :development, :test, :staging do
  gem 'pry'
  gem 'pry-byebug'
end

#configure airbrake first
gem 'airbrake'

gem 'rails', '5.2.4.3'
gem 'abstract_method'
gem 'activeadmin', github: 'activeadmin'
gem 'addressable'
gem 'aws-sdk', '~> 2'
# apipie 0.3.4 has a couple issues
gem 'apipie-rails', github: 'Apipie/apipie-rails', ref: '928bd858fd14ec67eeb9483ba0d43b3be8339608'
gem 'bootstrap-sass', '~> 3.3.5'
gem 'coffee-rails', '>= 4.2.2'
gem 'devise', '>= 4.4.2'
gem 'engineyard', '~> 3.2'
gem 'enumerize', '>= 1.1.1'
gem 'exifr'

gem 'font-awesome-rails'                                                                                                                  [53/7472]
gem 'font-awesome-sass', '~> 4.2.0'
gem 'geokit-rails', '>= 2.1.0'
gem 'haml'
gem 'haml-rails', '>= 0.9.0'
gem 'health_check', '>= 1.5.1'
gem 'html2haml'
gem 'indefinite_article', '>= 0.2.4'
gem 'jbuilder', '~> 2.6', '>= 2.6.4'
gem 'jquery-rails', '>= 4.1.1'
gem 'json-compare'
gem 'kaminari', '>= 0.16.3'
gem 'pg'
gem 'sqlite3'
gem 'nested_form'
gem 'newrelic_rpm'
gem 'ey_config'
gem 'oauth'
gem 'oauth2'
gem 'paper_trail', '~> 4.0.2'
gem 'paranoia', '>= 2.4.1'
gem 'pundit', '>= 1.1.0'
gem 'resque'
# TODO: may want to add this to track status of jobs
# gem 'resque-status'
gem 'rolify'
gem 'rmagick', :require => 'RMagick'
gem 'ruby-prof'
gem 'sass-rails', '~> 5.0', '>= 5.0.5'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'seed-fu', '>= 2.3.6'
gem 'sendgrid'

gem 'simple_form', '>= 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'woocommerce_api'
gem 'xmp', git: 'git@github.com:redcap97/xmp.git', :branch => "update-nokogiri"
gem 'slack-api'

#gem 'turbolinks'

# gem 'capistrano-rails', group: :development

group :staging, :development, :test do
  gem 'ffaker'
  gem 'factory_girl_rails', '>= 4.7.0'
end

group :development, :test do
  gem 'database_cleaner'
  gem 'letter_opener'
  gem 'rails-erd', '>= 1.4.7'
  gem 'rspec-activemodel-mocks', '>= 1.0.3'
  gem 'rspec-mocks'
  gem 'rspec-rails', '>= 3.5.0'
  gem 'simplecov'
  gem 'simplecov-csv'
  gem 'simplecov-rcov'
  gem 'timecop'
  gem 'travis', '>= 1.7.7'
end

