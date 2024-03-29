source 'https://rubygems.org'

source 'https://rubygems.org'

 git_source(:github) do |repo_name|
   repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
   "https://github.com/#{repo_name}.git"
 end

 # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
 gem 'rails', '~> 5.1.2'

 group :production do
   # Use pg as the production database for Active Record
   gem 'pg'
   gem 'rails_12factor'
 end

 group :development do
   # Use sqlite3 as the development database for Active Record
   gem 'sqlite3'
   gem 'web-console', '~> 2.0'
 end

 # Use Puma as the app server
 gem 'puma', '~> 5.6'
 # Use SCSS for stylesheets
 gem 'sass-rails', '~> 5.0'
 # Use Uglifier as compressor for JavaScript assets
 gem 'uglifier', '>= 1.3.0'

 # Use jquery as the JavaScript library
 gem 'jquery-rails'
 # Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
 gem 'turbolinks', '~> 5'
 # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
 gem 'jbuilder', '~> 2.5'

 gem 'thor', '0.19.1'

 gem 'bootstrap-sass'

 gem 'devise'

 gem 'figaro', '1.0'

 gem "pundit"

 gem "rolify"

 gem "stripe"

 gem "redcarpet"

 group :development do
   gem 'listen', '~> 3.0.5'
   gem "better_errors"
   gem "binding_of_caller"
 end

 group :test do

   gem 'shoulda'
   gem 'faker'
   gem 'factory_girl_rails'
   gem 'simplecov'
   gem 'pundit-matchers', '~> 1.3.1'
   gem 'stripe-ruby-mock', '~> 2.5.0', :require => 'stripe_mock'
 end

 group :development, :test do
   gem 'rspec-rails', '~>3.0'
   gem 'rails-controller-testing'
   gem 'pry-rails'
 end
