source 'https://rubygems.org'

gemspec

platforms :mri_18 do
  gem 'ruby-debug', '>= 0.10.3'
end

platforms :mri_19 do
  gem 'debugger' if RUBY_VERSION < '2.0'
end

group :development do
  gem 'pry'
end
