source "https://rubygems.org"

# GitHub Pages official gem
gem "github-pages", "~> 232", group: :jekyll_plugins

# Плагины GitHub Pages
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"  # RSS feed
  gem "jekyll-sitemap"          # Sitemap.xml
  gem "jekyll-paginate"         # Пагинация
  gem "jekyll-seo-tag"          # SEO-теги
end

# Оптимизация для Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Поддержка часовых поясов для Windows
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
