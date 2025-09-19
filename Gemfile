source "https://rubygems.org"

# Use the GitHub Pages stack (pins Jekyll + all supported plugins)
gem "github-pages", group: :jekyll_plugins

# Needed for remote_theme (Pages includes it, but keep for local runs)
gem "jekyll-remote-theme"

# Optional plugin (also included by github-pages, but safe to keep)
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Ruby 3+ needs WEBrick for `jekyll serve`
gem "webrick", "~> 1.8"

# Windows / JRuby extras
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
