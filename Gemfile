source 'https://rubygems.org'

group :lint do
  gem 'foodcritic', '~> 5.0'
  gem 'rubocop', '~> 0.18'
  gem 'rainbow', '< 2.0'
  gem 'rake'
end

group :unit do
  gem 'mixlib-versioning'
  # gem 'mixlib-install', '~> 0.8.0.alpha'
  gem 'mixlib-install', path: '/Users/patrickwright/github/mixlib-install'
  gem 'chef-sugar'
  gem 'chefspec'
  gem 'chef-dk'

  # Pin nokogiri to 1.6.7 until the new version can install in travis.
  gem 'nokogiri', '= 1.6.7'
end

group :development do
  gem 'ruby_gntp'
  gem 'growl'
  gem 'rb-fsevent'
  gem 'guard', '~> 2.4'
  gem 'guard-kitchen'
  gem 'guard-foodcritic'
  gem 'guard-rspec'
  gem 'guard-rubocop'
end

# Run kitchen using Chef DK bundled set of gems.
