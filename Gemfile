source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.6'
gem 'puma'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'jquery-rails'
# gem 'turbolinks', '~> 5'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'sdoc', '~> 0.4.0', group: :doc
gem 'pg'
# gem 'haml'
gem 'haml-rails'
gem 'coffee-rails'
gem 'bootstrap-sass'
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.2'

gem 'jwt'
gem 'active_model_serializers'
gem 'chartkick'
gem 'groupdate'

gem 'jquery-atwho-rails'

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'byebug'
  # Access an PRY console on exception pages or by using binding.pry anywhere in the code.
  gem 'pry'
  gem 'pry-rails'
  gem 'pry-byebug'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production do
  gem 'rails_12factor'
end
