require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('yozm_oauth', '0.1.0') do |p|
	p.description = 'Yozm OAuth API client library for ruby'
	p.url = 'http://github.com/thefron/yozm_oauth'
	p.author = 'Hoseong Hwang'
	p.email = 'thefron@wafflestudio.com'
	p.ignore_pattern  = ["tmp/*", "script/*"]
	p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }
