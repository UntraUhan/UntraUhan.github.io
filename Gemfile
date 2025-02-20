source "https://rubygems.org"

# Use GitHub Pages official gem
gem "github-pages", "~> 232", group: :jekyll_plugins

# Other required plugins for GitHub Pages
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"  # RSS feed
  gem "jekyll-sitemap"          # Sitemap.xml for SEO
  gem "jekyll-paginate"         # Pagination support
  gem "jekyll-seo-tag"          # SEO optimization
end

# Performance optimization on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Timezone support for Windows
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
