source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.0.0.beta1'

group :development, :test do
  gem 'sqlite3', '1.3.7'
  gem 'rspec-rails', '2.13.0'
  gem 'guard-rspec', '2.5.0'
  gem 'spork-rails', github: 'koriroys/spork-rails'
  gem 'guard-spork', '1.5.0'
end

group :test do
  gem 'selenium-webdriver', '2.0'
  gem 'capybara', '2.1.0.beta1'

  # Uncomment these lines on OS X.
  # gem 'rb-fsevent', '0.9.3', :require => false
  # gem 'growl', '1.0.3'

  gem 'rb-inotify', '0.9.0'
  gem 'libnotify', '0.8.0'

  # Uncomment these lines on Windows.
  # gem 'rb-fchange', '0.0.6'
  # gem 'rb-notifu', '0.0.4'
  # gem 'win32console', '1.3.2'
end

group :assets do
  gem 'sass-rails',   '4.0.0.beta1'
  gem 'coffee-rails', '4.0.0.beta1'
  gem 'uglifier', '1.0.3'
end

gem 'jquery-rails', '2.2.1'
gem 'turbolinks', '1.0.0'
gem 'jbuilder', '1.0.1'

group :production do
  gem 'pg', '0.14.1'
end
