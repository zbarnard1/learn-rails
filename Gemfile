source 'https://rubygems.org'
ruby '2.4.1'
git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '5.1.2'
gem 'jquery-rails'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'sendgrid-ruby'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# learn-rails
gem 'bootstrap-sass'
gem 'gibbon'
gem 'high_voltage'
gem 'simple_form'
group :development do
  gem 'better_errors'
  gem 'rails_layout'
  gem 'sqlite3'
end
group :production do
  gem 'pg'
end
group :test do
  gem 'minitest-spec-rails'
  gem 'minitest-rails-capybara'
end