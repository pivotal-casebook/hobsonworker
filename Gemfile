# A sample Gemfile
source "http://rubygems.org"

# gem "hobson", git: "https://github.com/deadlyicon/hobson.git"
# gem "hobson", path: "~/workspace/hobson"
gem "hobson", :git=> "git://github.com/Casecommons/hobson.git", :branch => "casebook" 
# gem "hobson", path: "~/workspace/hobson"

# A dependency of hobson, but we need this commit for Ruby 1.9:
# https://github.com/deadlyicon/redis-slave/commit/22437f0e893b7cfee1997b82dc45cea72dcb5613
# Remove this line when >= 0.0.4 is available from RubyGems.
gem "redis-slave", ">= 0.0.4", git: "https://github.com/deadlyicon/redis-slave.git"

group :debug19 do
  gem 'ruby_core_source'
  gem 'linecache19'
  gem 'ruby-debug-base19', '0.11.26'
  gem 'ruby-debug19', :require => 'ruby-debug'
end
