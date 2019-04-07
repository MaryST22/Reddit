source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.7'
gem 'pg'
gem 'tzinfo-data'
gem 'devise', '~> 4.2'
gem 'bootstrap-sass', '~> 3.4', '>= 3.4.1'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'acts_as_votable', '~> 0.10.0'

group :doc do
  gem 'sdoc', require: false
end
