source 'https://rubygems.org'
 
 git_source(:github) do |repo_name|
 repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
   "https://github.com/#{repo_name}.git"
 end
 
 
 gem 'rails', '~> 5.0.2'
 gem 'puma', '~> 3.0'
 gem 'sass-rails', '~> 5.0'
 gem 'uglifier', '>= 1.3.0'
 gem 'coffee-rails', '~> 4.2'
 gem 'jquery-rails'
 gem 'turbolinks', '~> 5'
 gem 'jbuilder', '~> 2.5'
 gem 'bootstrap-sass', '~> 3.0.3.0'
 gem "paperclip", "~> 3.1"
 gem "paperclip-dropbox", ">= 1.1.7"
 gem "figaro"

 group :production do
  gem 'pg'
  gem 'rails_12factor'
end

group :development, :test do
  gem 'sqlite3'
end

 #group :development, :test do
   #gem 'byebug', platform: :mri
 #end
 
 group :development do
   gem 'web-console', '>= 3.3.0'
 end

 group :doc do
  gem 'sdoc', require: false
end
 
 gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]