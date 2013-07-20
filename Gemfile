source "http://ruby.taobao.org/"

gem 'bundler', '>= 1.0.10'
gem 'nats', :require => 'nats/client'
gem 'eventmachine', :git => 'https://github.com/cloudfoundry/eventmachine.git', :branch => 'release-0.12.11-cf'
gem 'em-http-request', '~> 1.0.0.beta.3', :require => 'em-http'

gem 'rack', :require => ["rack/utils", "rack/mime"]
gem 'rake'
gem 'thin'
gem 'yajl-ruby', :require => ['yajl', 'yajl/json_gem']

# FIXME: we should use the CF org instead of Jesse's personal repo...
gem 'vcap_common', '~> 1.0.8', :git => 'https://github.com/cloudfoundry/vcap-common.git', :ref => '9673dced'
gem 'vcap_logging', :require => ['vcap/logging'], :git => 'https://github.com/cloudfoundry/common.git', :ref => 'e36886a1'

gem 'sys-filesystem', '~> 1.0.0'

group :test do
  gem "rspec"
  gem "rcov"
  gem "ci_reporter"
end
