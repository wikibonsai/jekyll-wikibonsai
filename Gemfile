# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# run
gem "rouge", "~> 3.26.1"
# dev
gem "rake", "~> 13.0"
gem "rspec", "~> 3.0"
gem "rubocop", "~> 1.7"

# note: keep in-sync with with jekyll-garden.gemspec
gem "jekyll", "~> 4.2.0"
group :jekyll_plugins do
  # official
  gem "jekyll-feed", "~> 0.15.1"
  gem "jekyll-seo-tag", "~> 2.7.1"
  gem "jekyll-sitemap", "~> 1.4.0"
  # ashmaroli
  gem "jekyll-data", "~> 1.1.1"
  # local
  gem "jekyll-id", "~> 0.0.2"
  gem "jekyll-semtree", "~> 0.0.3"
  gem "jekyll-wikirefs", "~> 0.0.14"
  gem "jekyll-graph", "~> 0.0.11"
end

gem "webrick", "~> 1.7"
