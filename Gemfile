# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# gem "rails"

gem "jekyll", "~> 4.1"

group :jekyll_plugins do
    gem "jekyll-feed", "~> 0.12"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
    gem "tzinfo", "~> 1.2"
    gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
