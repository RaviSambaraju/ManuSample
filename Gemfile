source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end
gem 'rails', '~> 5.0.5'
gem "mysql2", "~> 0.3.11"
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
group :development, :test do
  gem 'byebug', platform: :mri
end
group :development do
  gem 'web-console', '>= 3.3.0'
end
gem 'devise', '~> 4.3'
gem 'paperclip', '~> 5.1'
gem 'rghost', '~> 0.9.5'
gem 'cocaine', '~> 0.5.5'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'
gem 'searchkick', '~> 2.3', '>= 2.3.1'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
