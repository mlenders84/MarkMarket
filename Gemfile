source 'https://rubygems.org'
ruby '2.6.3'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }


gem 'rails', '~> 6.0.3', '>= 6.0.3.4'
gem 'puma', '~> 4.1'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 4.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'
gem 'bootsnap', '>= 1.4.2', require: false

gem 'materialize-sass', '~> 1.0.0'

gem 'devise'

gem "paperclip", "~> 6.0.0"

gem 'bootstrap-sass'

gem 'will_paginate', '~> 3.1.0'

gem 'will_paginate-materialize', git: 'https://github.com/mldoscar/will_paginate-materialize', branch: 'master'

gem 'friendly_id', '~> 5.4.0'

gem 'dotenv-rails', groups: [:development, :test]

gem 'stripe', '~> 5.11.0'

gem 'aasm'





group :development, :test do

  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'sqlite3', '~> 1.4'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
	end

group :development do

  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.2'

  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  
  gem 'webdrivers'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
