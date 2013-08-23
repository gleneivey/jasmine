source :rubygems
gem "rake"
gem "jasmine", :git => 'https://github.com/pivotal/jasmine-gem.git', :ref => '2afdf2b690d79d4e4582900becab15ff9d36c395'

unless ENV["TRAVIS"]
  group :debug do
    gem 'debugger'
  end
end
 
gemspec
