source "https://rubygems.org"

group :test do
  gem "rake"
  gem "puppet", ENV['PUPPET_VERSION'] || '~> 3.8.0'
  gem "rspec-puppet", :git => 'https://github.com/rodjek/rspec-puppet.git'
  gem "puppetlabs_spec_helper"
end

group :development do
  gem "travis"
  gem "travis-lint"
  gem "puppet-blacksmith"
end
