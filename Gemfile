if RUBY_VERSION =~ /1.9/
  Encoding.default_external = Encoding::UTF_8
  Encoding.default_internal = Encoding::UTF_8
end

source 'https://rubygems.org'

gem 'rails', '~> 4.2.0'



gem 'ey_config'
gem 'rails_autolink'
gem 'simple_form'

# Assets
gem 'jquery-rails'
gem 'sass-rails'
gem 'coffee-rails'
gem 'uglifier'

platform :ruby do
  gem 'mysql2'

  gem 'newrelic_rpm'
  gem 'json'
  gem 'minitest'
  gem 'psych'
  gem 'racc'
end


# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :development, :test do

end
