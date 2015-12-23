source 'https://rubygems.org'

gem 'rails'
gem 'rails-i18n'

gem 'pg'
gem 'dalli'
gem 'uglifier'
gem 'coffee-rails'

gem 'sass-rails'
gem 'sprockets-rails'
gem 'compass-rails'

gem 'slim-rails'
gem 'jbuilder'

gem 'unicorn'
gem 'jquery-rails'
gem 'turbolinks'

gem 'simple_form'
gem 'simple_form-magic_submit'

gem 'awesome_print'
gem 'pry-rails'
gem 'pry-stack_explorer'
gem 'byebug'
gem 'pry-byebug'
gem 'marco-polo'

gem 'unicode'
gem 'rs_russian'

gem 'devise'
gem 'devise-async'

gem 'meta-tags', require: 'meta_tags'
gem 'enumerize'

gem 'sidekiq'
gem 'sidekiq-limit_fetch'
gem 'sidekiq-status' # for unscheduling sidekiq tasks

gem 'sinatra', require: false
gem 'whenever', require: false
gem 'attr_extras'
gem 'active_model_serializers'

gem 'non-stupid-digest-assets'

gem 'faraday' # для http запросов
gem 'faraday_middleware'

group :production, :staging do
  gem 'honeybadger'
end

gem 'draper' # presenters
gem 'cancancan'

gem 'state_machines-activerecord'
gem 'activerecord-import'
gem 'retriable'

group :development do
  gem 'mactag' # для тегфайлов вима
  gem 'letter_opener_web'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'bullet'
  gem 'active_record_query_trace'

  gem 'capistrano', require: false
  gem 'capistrano-rails', require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano-file-permissions', require: false, github: 'morr/file-permissions'
  gem 'rvm1-capistrano3', require: false
  gem 'airbrussh', require: false
end

group :development, :staging do
  gem 'rails_db_info'
end

group :development, :test do
  gem 'quiet_assets'

  gem 'rb-inotify', require: false
  gem 'rb-fsevent', require: false
  gem 'rb-fchange', require: false

  gem 'rspec'
  gem 'rspec-rails'
  gem 'rspec-mocks'
  gem 'rspec-collection_matchers'
  gem 'rspec-its'

  gem 'spring'
  gem 'spring-commands-rspec'

  gem 'timecop'

  gem 'guard', require: false
  gem 'guard-rspec', require: false
  gem 'guard-bundler', require: false
  gem 'guard-spring', require: false
  gem 'guard-pow', require: false
end

group :test do
  gem 'factory_girl_rails', require: false
  gem 'factory_girl-seeds', require: false
  gem 'webmock'
  gem 'shoulda-matchers'
  gem 'database_cleaner'
  gem 'capybara'
  gem 'vcr', github: 'morr/vcr' # TODO: убрать github опцию, когда примут пулреквест vcr/vcr: Pull Request #418
end
# assets
source 'https://rails-assets.org' do
  gem 'rails-assets-jquery'
end
