#
# Copyright 2013-2014, SUSE LINUX Products GmbH
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#   http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#

source 'https://rubygems.org'

group :development do
  gem 'closure-compiler', '~> 1.1.10'
  gem 'sass', '~> 3.2.19'
  gem 'sprockets-standalone', '~> 1.2.1'
  gem 'sprockets', '~> 2.11.0'
  gem 'rspec', '~> 3.1.0'
end

group :test do
  gem 'simplecov', require: false

  if ENV['CODECLIMATE_REPO_TOKEN']
    gem 'coveralls', require: false
    gem 'codeclimate-test-reporter', require: false
  end
end
