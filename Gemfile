source 'https://rubygems.org'

gem 'rails', '3.2.13'


group :development, :test do
  gem 'sqlite3', '1.3.5'
  gem 'rspec-rails', '2.11.0'
  gem 'guard-rspec', '1.2.1'
  gem 'guard-spork', :github => 'guard/guard-spork'
 # gem 'guard-spork', '1.2.0'
  gem 'spork', '0.9.2'

end

group :assets do
  gem 'sass-rails',   '3.2.5'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
end

gem 'jquery-rails', '2.0.2'

# Тестовые гемы для Linux

group :test do
  gem 'capybara', '1.1.2'
  gem 'rb-inotify', '0.8.8'
  gem 'libnotify', '0.5.9'
end


# heroku gems

gem 'heroku'
gem 'taps'
group :production do
  gem 'rails_12factor'
  gem 'pg', '0.17.0'
end
