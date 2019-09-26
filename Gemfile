# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|docs| "https://github.com/#{docs}" }

ruby "2.6.2"

gem "github-pages", group: :jekyll_plugins
gem "jekyll", "~> 3.5"
gem "minimal-mistakes-jekyll"
gem "tzinfo-data"
gem "wdm", "~> 0.1.0" if Gem.win_platform?
gem 'html-proofer'
gem 'rack-contrib'
gem 'rake'

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jemoji"
  gem "jekyll-algolia"
  gem 'jekyll-last-modified-at'
end
# gem "rails"
