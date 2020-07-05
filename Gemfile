source "https://rubygems.org"

gemspec

if RUBY_VERSION.split(".")[1].to_i > 0
  gem "rspec-benchmark"
end

group :tools do
  gem "yard", "~> 0.9.12"
end

group :metrics do
  gem "coveralls", "~> 0.8.22"
  gem "simplecov", "~> 0.16.1"
  gem "yardstick", "~> 0.9.9"
end

group :benchmarks do
  gem "benchmark-ips", "~> 2.7.2"
end
