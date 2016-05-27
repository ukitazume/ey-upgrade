source 'https://rubygems.org'


# putting this first so we have pry available when loading other gems
group :development, :test, :staging do
  gem 'pry'
  gem 'pry-byebug'
end

#configure airbrake first
gem 'airbrake'

gem 'rails', '4.2.6'
gem 'abstract_method'
gem 'activeadmin'
gem 'addressable'
gem 'aws-sdk', '~> 2'
# apipie 0.3.4 has a couple issues
gem 'apipie-rails', github: 'Apipie/apipie-rails', ref: '928bd858fd14ec67eeb9483ba0d43b3be8339608'
gem 'bootstrap-sass', '~> 3.3.5'
gem 'coffee-rails'
gem 'devise'
gem 'engineyard', '~> 3.2'
gem 'enumerize'
gem 'exifr'

gem 'font-awesome-rails'                                                                                                                  [53/7472]
gem 'font-awesome-sass', '~> 4.2.0'
gem 'geokit-rails'
gem 'haml'
gem 'haml-rails'
gem 'health_check'
gem 'html2haml'
gem 'indefinite_article'
gem 'jbuilder', '~> 2.0'
gem 'jquery-rails'
gem 'json-compare'
gem 'kaminari'
gem 'mysql2'
gem 'sqlite3'
gem 'nested_form'
gem 'newrelic_rpm'
gem 'ey_config'
gem 'oauth'
gem 'oauth2'
gem 'paper_trail', '~> 4.0.0'
gem 'paranoia'
gem 'pundit'
gem 'resque'
# TODO: may want to add this to track status of jobs
# gem 'resque-status'
gem 'rolify'
gem 'rmagick'
gem 'ruby-prof'
gem 'sass-rails', '~> 5.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'seed-fu'
gem 'sendgrid'

gem 'simple_form'
gem 'uglifier', '>= 1.3.0'
gem 'woocommerce_api'
gem 'xmp', git: 'git@github.com:redcap97/xmp.git', :branch => "update-nokogiri"
gem 'slack-api'

#gem 'turbolinks'

# gem 'capistrano-rails', group: :development

group :staging, :development, :test do
  gem 'ffaker'
  gem 'factory_girl_rails'
end

group :development, :test do
  gem 'database_cleaner'
  gem 'letter_opener'
  gem 'rails-erd'
  gem 'rspec-activemodel-mocks'
  gem 'rspec-mocks'
  gem 'rspec-rails'
  gem 'simplecov'
  gem 'simplecov-csv'
  gem 'simplecov-rcov'
  gem 'timecop'
  gem 'travis', '>= 1.7.7'
end

