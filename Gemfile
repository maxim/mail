source 'http://rubygems.org'

gem "activesupport", ">= 2.3.6.pre"
gem "tlsmail" if RUBY_VERSION <= '1.8.6'
gem "mime-types"
gem "treetop", ">= 1.4.5"

group :test do
  gem "rcov"
  gem "rake"
  gem "bundler", "~> 0.9.10"
  gem "cucumber"
  gem "rspec"
  gem "diff-lcs"
  gem "ruby-debug" if RUBY_VERSION < '1.9' and RUBY_PLATFORM != 'java'
end
