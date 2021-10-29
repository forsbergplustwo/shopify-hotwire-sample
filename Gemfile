source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.2'

# backend
gem 'rails', '~> 6.1.4'
gem 'pg', '~> 1.1'
gem 'redis'
gem 'puma', '~> 5.0'
gem 'bootsnap', '>= 1.7.5', require: false
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'dotenv-rails', '~> 2.7'

# shopify
gem 'shopify_app', github: 'kirillplatonov/shopify_app'
gem 'polaris_view_components', '~> 0.5.0'

# frontend
gem 'jsbundling-rails'
gem 'turbo-rails', '~> 7.1'
gem 'stimulus-rails'
gem 'hotwire-livereload'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 4.1.0'
  gem 'foreman', '~> 0.87.2'
end

group :test do
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end
