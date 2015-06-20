def opsworks_cookbook(name, version = '>= 0.0.0', options = {})
  cookbook name, version, { path: "/path/to/repo/#{name}" }.merge(options)
end

cookbook 'elasticsearch'
cookbook 'logstash'
cookbook 'java'
cookbook 'git'

source 'https://supermarket.chef.io'
metadata

group :integration do
  cookbook 'apt', '~> 2.0'
end

