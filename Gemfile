source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# DOC: 20210529, https://pages.github.com/versions/
gem "github-pages", group: :jekyll_plugins

# NOTE: 20210529, commented in favor of the gem "github-pages" which depends on "jekyll"
# gem "jekyll", "~> 4.0.0"

# NOTE: 20210529, commented in favor of the theme "just-the-docs"
# gem "minima", "~> 2.5"
gem "just-the-docs"

group :jekyll_plugins do
# NOTE: 20210529, commented commented again by knowing the fact it is already included by github-pages
# NOTE: 20210529, uncommented by removing version definiton and run `bundle update jekyll-feed`
# NOTE: 20210529, commented because of conflict requirements from github-pages and minima
#   gem "jekyll-feed"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
