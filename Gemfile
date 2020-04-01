source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.1'
# Use postgresql as the database for Active Record
gem 'sqlite3'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'rubocop', '~> 0.71.0', require: false
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
gem 'devise'
# gem 'devise_token_auth'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
gem 'simplecov', '0.17.1', require: false, group: :test
gem 'simplecov-console', require: false
gem 'sass-rails', '~> 5.0'


# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# gem required to add user authentication


group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
  gem 'rspec-rails', '~> 3.5'

end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'web-console', '>= 3.3.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]




# source 'https://rubygems.org'
# git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# ruby '2.6.3'



# # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
# gem 'rails', '~> 6.0.2', '>= 6.0.2.2'
# # Use sqlite3 as the database for Active Record
# gem "sqlite3", :platform => [:ruby, :mswin, :mingw]
# # Use Puma as the app server
# gem 'puma', '~> 4.1'
# # Use SCSS for stylesheets
# gem 'sass-rails', '>= 6'
# # Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
# gem 'webpacker', '~> 4.0'
# # Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
# gem 'turbolinks', '~> 5'
# # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.7'
# # Use Redis adapter to run Action Cable in production
# # gem 'redis', '~> 4.0'
# # Use Active Model has_secure_password
# # gem 'bcrypt', '~> 3.1.7'

# # Use Active Storage variant
# # gem 'image_processing', '~> 1.2'

# # Reduces boot times through caching; required in config/boot.rb
# gem 'bootsnap', '>= 1.4.2', require: false

# group :development, :test do
#   # Call 'byebug' anywhere in the code to stop execution and get a debugger console
#   gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
#   gem 'rspec-rails', '~> 3.5'
 
# end

# group :development do
#   # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
#   gem 'web-console', '>= 3.3.0'
#   gem 'listen', '>= 3.0.5', '< 3.2'
#   # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
#   gem 'spring'
#   gem 'spring-watcher-listen', '~> 2.0.0'
# end

# group :test do
#   # Adds support for Capybara system testing and selenium driver
#   gem 'capybara', '>= 2.15'
#   gem 'selenium-webdriver'
#   # Easy installation and use of web drivers to run system tests with browsers
#   gem 'webdrivers'
#   gem 'simplecov', '0.17.1'
#   gem 'simplecov-console'
  
# end

# # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]