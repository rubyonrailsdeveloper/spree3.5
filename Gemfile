source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.6', '>= 5.1.6.1'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'spree', '~> 3.5.0'
gem 'spree_auth_devise', '~> 3.4'
gem 'spree_gateway', '~> 3.4'

gem 'spree_gift_card' , github: 'vinsol-spree-contrib/spree_gift_card'
gem 'spree_favorite_products', github: 'vinsol-spree-contrib/spree_favorite_products'
gem 'spree_product_subscriptions', github: 'rubyonrailsdeveloper/spree-product-subscriptions'
gem 'spree_address_auto_complete', git: 'https://github.com/vinsol-spree-contrib/spree_address_auto_complete', branch: 'master'
gem 'spree_promo_users_codes', github: 'vinsol-spree-contrib/spree_promo_users_codes', branch: 'master'
gem 'spree_quotes_management', github: 'vinsol-spree-contrib/spree-quotes-management'
gem 'spree_related_products', github: 'spree-contrib/spree_related_products'
gem 'spree_best_sellers', github: 'rubyonrailsdeveloper/spree_best_seller'

gem 'spree_wishlist', github: 'spree-contrib/spree_wishlist', branch: 'master'
gem 'spree_email_to_friend', github: 'spree-contrib/spree_email_to_friend', branch: 'master'

gem 'spree_marketing', github: 'vinsol-spree-contrib/spree_marketing'
gem 'spree_events_tracker', github: 'vinsol-spree-contrib/spree_events_tracker'
gem 'spree_contact_us', github: 'rubyonrailsdeveloper/spree_contactUs'