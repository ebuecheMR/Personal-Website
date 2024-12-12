source "https://rubygems.org"

# Specify the Jekyll version
gem "jekyll", "~> 3.9.2"
gem "minima" # Replace "minimal" with "minima"

# Add required plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem "jekyll-sitemap"
  gem "jekyll-mentions"
  gem "jekyll-paginate"
  gem "jekyll-seo-tag"
  gem "jekyll-redirect-from"
end

# Compatibility for Markdown parsing
gem "kramdown-parser-gfm"

# Include `webrick` for Ruby 3.x compatibility
gem "webrick"

# Ensure timezone data compatibility for Windows
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance booster for directory watching on Windows
gem "wdm", "~> 0.1.0", platforms: [:mingw, :mswin, :x64_mingw]

# Add `actionpack` if specifically required by your project
