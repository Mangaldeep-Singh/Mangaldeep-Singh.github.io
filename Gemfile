source "https://rubygems.org"

gem "jekyll", "3.9.5"
gem "github-pages", group: :jekyll_plugins
gem "jekyll-theme-primer"
gem "jekyll-feed", "~> 0.12"
gem "jekyll-sitemap"
gem "jekyll-seo-tag"
gem "jekyll-toc"
gem 'webrick'
gem 'jekyll-postcss'
gem 'jemoji'
gem 'kramdown-parser-gfm'

# Performance-booster for watching directories and fix for livereload.
gem "wdm", "~> 0.1.1", install_if: Gem.win_platform?

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end
