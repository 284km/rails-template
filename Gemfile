source 'https://rubygems.org'

# なんかだめなとき
ENV['NOKOGIRI_USE_SYSTEM_LIBRARIES'] = 'YES'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.8'

# Use sqlite3 as the database for Active Record
gem 'sqlite3'

# for heroku
# gem 'sqlite3', group: [:development, :test]
# gem 'pg', group: :production
# gem 'rails_12factor', group: :production

# Use mysql as the database for Active Record
# gem 'mysql2'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]


# Put Gemfile.local to use arbitrary gems for your use case.
path = Pathname.new("Gemfile.local")
eval(path.read) if path.exist?

gem 'compass-rails'
gem "font-awesome-rails"
gem 'slim-rails'

# gem 'omniauth'
# gem 'omniauth-twitter'

gem 'kaminari'
gem 'kaminari-bootstrap'


group :development, :test do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'byebug'
  gem 'pry-byebug'
  gem "pry-stack_explorer"

  gem "capybara"
  gem "selenium-webdriver"
  gem "database_cleaner"
  gem "shoulda-matchers"

  gem "teaspoon"
end

group :development do
  # rails c で pry が立ち上がる
  gem 'pry-rails'
  gem 'pry-doc'

  # print を見やすくするやつ
  gem 'awesome_print'
  # Source Map
  gem 'coffee-rails-source-maps'

#  rails 4 対応してない? bundle install でエラー出たからコメントアウト中
#  gem 'sass-rails-source-maps'

  # 分かり易いエラー画面
  gem 'better_errors'
  # better_errorsの画面上にirb/pry(REPL)を表示する
  gem 'binding_of_caller'

  # asset 系のログを off にしてくれる。必要なのかは試していない。
  gem 'quiet_assets'

  # スキーマ情報がmodelファイルの中でわかるようにする。
  ### bundle install したら、
  ### bundle exec annotate する。
  gem 'annotate', :git => 'git://github.com/ctran/annotate_models.git'

  gem 'rack-mini-profiler'
end

group :test do
  gem "autodoc"
  gem "coveralls", require: false
  gem "response_code_matchers"
  gem "rspec-json_matcher"
  gem "simplecov"
end

# gem 'rails-assets-lodash'
# gem 'rails-assets-backbone'
# gem 'rails-assets-backbone.stickit'
# gem 'rails-assets-backbone.wreqr'
# gem 'rails-assets-backbone.babysitter'
# gem 'rails-assets-marionette'

gem 'rb-readline'


# gem "clockwork"
# gem "foreman"
# gem "puma"
# gem "redis"
# gem "resque"
# gem "weak_parameters"




