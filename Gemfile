source "http://rubygems.org"

# Specify your gem's dependencies in representative_view.gemspec
gemspec

if ENV["ACTIONPACK_VERSION"]
  gem "actionpack", ENV["ACTIONPACK_VERSION"]
end

gem "nokogiri", ">= 1.5.0"

group :test do
  gem "rake", "~> 0.8.7"
  gem "rspec", "~> 3.7.0"
  gem "rr", "~> 1.0.2"
  gem "minstrel"
end
