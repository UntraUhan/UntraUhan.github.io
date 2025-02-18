source "https://rubygems.org"

# 🔹 Поддержка GitHub Pages (автоматически ставит нужные версии Jekyll и Minima)
gem "github-pages", group: :jekyll_plugins

# 🔹 Дополнительные плагины Jekyll
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"        # RSS-фид
  gem "jekyll-sitemap"                # Sitemap.xml для SEO
  gem "jekyll-paginate"               # Пагинация
  gem "jekyll-seo-tag"                # SEO-оптимизация
end

# 🔹 Поддержка часовых зон на Windows
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# 🔹 Улучшение работы Jekyll на Windows
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# 🔹 Поддержка HTTP в JRuby
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]


