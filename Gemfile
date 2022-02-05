# frozen_string_literal: true

source "https://rubygems.org"

ruby "2.7.2"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "jekyll", "~> 4.2.0"
gem "jekyll-last-modified-at", git: "https://github.com/maximevaillancourt/jekyll-last-modified-at", branch: "add-support-for-files-in-git-submodules"
gem "nokogiri"
gem "webrick", "~> 1.7"

group :development do
  gem "pry", "~> 0.14.1"
end
