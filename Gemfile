source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.6.2'

git_source :github do |name|
  "https://github.com/#{name}.git"
end

gem 'mime-types', '~> 3.2.2', require: 'mime/types/columnar'

# Gems required in all environments
if ENV["RAILS_MASTER"] == '1'
  gem 'rails', git: 'https://github.com/rails/rails.git'
else
  gem 'rails', '6.0.0.beta2'
end

gem 'bluecloth'
gem 'dalli'
gem 'devise', git: 'https://github.com/plataformatec/devise'
gem 'responders', git: 'https://github.com/plataformatec/responders'
gem 'git_hub_bub'
gem 'jquery-rails'
gem 'local_time', '2.1.0'
gem 'maildown', git: 'https://github.com/schneems/maildown'
gem 'omniauth', '~> 1.9.0'
gem 'omniauth-github'
gem 'pg'
gem 'puma'
gem 'rack-timeout'
gem 'rrrretry'
gem 'valid_email'
gem 'warden', '1.2.8'
gem 'wicked'
gem 'will_paginate', '3.1.7'
# gem 'sass-rails', '6.0.0.beta1'
gem 'sassc'
gem 'sassc-rails'

gem 'autoprefixer-rails', '~> 9.5.0'
gem 'bourbon'
gem 'coffee-rails', '~> 4.2.0'
gem 'neat'
gem 'normalize-rails'
gem 'slim-rails'
gem 'uglifier', '>= 1.0.3'
gem 'render_async', '~> 2.0'

group :development do
  gem 'bullet', github: 'flyerhzm/bullet'
  gem 'listen'
  gem 'spring'
  gem 'web-console'
end

group :test do
  gem 'capybara', '3.16.1'
  # Not essential but helpful for save_and_open_page
  gem 'launchy'
  gem 'mocha', require: false
  gem 'rails-controller-testing'
  gem 'simplecov', require: false
  gem 'vcr'
  gem 'webmock'
end

group :development, :test do
  gem 'derailed_benchmarks'
  gem 'dotenv-rails'
  gem 'faker', require: false
  gem 'pry'
  gem 'rubocop', '0.58.2', require: false
end

gem 'rack-mini-profiler'

gem 'the_lone_dyno'

gem 'sidekiq'
gem 'sinatra', '~> 2.0.5'

gem 'aws-sdk', '~> 3'

gem 'mail', require: ['mail', 'mail/utilities', 'mail/parsers'] # parsers is used by `valid_email` and may be causing https://github.com/mikel/mail/issues/912#issuecomment-170121429

gem 'sprockets', github: "rails/sprockets"
gem 'sprockets-rails'

gem 'babel-transpiler'

gem 'scout_apm', '~> 2.4.20'
gem 'yard', '~> 0.9.18'

gem 'oj'
gem 'rack-canonical-host'
gem 'sentry-raven', github: "getsentry/raven-ruby" # @nateberkopec uses CodeTriage as a guineapig/canary for raven-ruby master

gem 'bootsnap', require: false
gem 'rbtrace'
gem 'redis-namespace'
gem 'stackprof'
gem 'prawn'
gem 'skylight', github: 'skylightio/skylight-ruby'

gem 'minitest', '5.11.3'
gem 'sitemap_generator'
gem 'premailer-rails', github: 'fphilipe/premailer-rails'

gem 'barnes'
gem 'puma_worker_killer'
