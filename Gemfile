source "https://rubygems.org"

gemspec :name => ""

gem "jruby-openssl", :platforms => :jruby
gem "rdf",           :git => "git://github.com/ruby-rdf/rdf.git", :branch => "develop"

group :test do
  gem "rdf-spec",    :git => "git://github.com/ruby-rdf/rdf-spec.git", :branch => "develop"
  gem "sparql",      :git => "git://github.com/ruby-rdf/sparql.git", :branch => "develop"
end

group :debug do
  gem 'shotgun'
  gem "wirble"
  gem "debugger", :platforms => [:mri_19, :mri_20]
end
