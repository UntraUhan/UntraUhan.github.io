source "https://rubygems.org"

# 🔹 Используем совместимую версию Jekyll для GitHub Pages
gem "github-pages", group: :jekyll_plugins

# 🔹 Дополнительные плагины
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jekyll-seo-tag"
end

# Поддержка часовых зон на Windows
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Оптимизация работы на Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
