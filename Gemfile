source 'https://rubygems.org'

gem 'rails', '6.1.7.3'

gem 'sass-rails', '>= 6.0.0'
gem 'uglifier', '>= 2.7.2'
gem 'jquery-rails', '~> 4.4.0'

gem 'pg',                   '~> 0.14'
gem 'carrierwave', '~> 1.3.2'
gem 'kaminari', '~> 1.2.1'
gem 'bugsnag', '~> 2.2.1'
gem 'draper', '~> 1.3.1'
gem 'fog', '~> 1.14.0'
gem 'simple_form', '~> 5.0.0'
gem 'simple_form_bootstrap3', '~> 0.3.0'
gem 'sidekiq', '~> 6.2.1'
gem 'thin', '~> 1.5.1'
gem 'open4',                '~> 1.3.0'
gem 'redcarpet', '~> 3.5.1'
gem 'slim',                 '~> 2.0.0'
gem 'dotenv-rails',         '~> 0.8'
gem 'sinatra', '~> 2.2.3', :require => false
gem 'active_model_serializers', '~> 0.8.1'
gem 'yajl-ruby', '~> 1.4.2', :require => 'yajl'
gem 'newrelic_rpm'
gem 'virtus',               '~> 1.0.1'
gem 'rails_warden', '~> 0.5.8'
gem 'pundit', '~> 0.3.0'
gem 'rack-robustness',      '~> 1.1.0'
gem 'rack-rewrite',         '~> 1.5.0'
gem 'oj',                   '~> 2.11'
gem 'oj_mimic_json',        '~> 1.0'
gem 'foreigner', '~> 1.7', '>= 1.7.4'

group :development do
  gem 'quiet_assets', '~> 1.0.2'
  gem 'foreman',        '~> 0.63.0'
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'immigrant'
end

group :test, :development do
  gem 'pry-rails',     '~> 0.3.2'
  gem 'rspec-rails', '~> 3.0.2'
  gem 'cane',          '~> 2.5.2'
  gem 'timecop',       '~> 0.7.1'
end

group :test do
  gem "rake", "~> 12.3.3"
  gem 'factory_girl_rails', '~> 4.2.1'
  gem 'capybara', '~> 2.4.4'
  gem 'poltergeist', '~> 1.6.0'
  gem 'database_cleaner',   '~> 1.0.1'
  gem 'guard'
  gem 'guard-rspec'
  gem 'rb-inotify', require: RUBY_PLATFORM.include?('linux') && 'rb-inotify'
  gem 'shoulda-matchers'
  gem 'coveralls',          require: false
  gem 'rspec-activemodel-mocks'
  gem 'chunky_png'
end

group :production do
  gem 'unicorn', '~> 4.7', '>= 4.7.0'
  gem 'dalli', '~> 3.2.3'
  gem 'unicorn-worker-killer', '~> 0.4.2'
end
