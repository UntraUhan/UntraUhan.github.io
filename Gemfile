source "https://rubygems.org"

# 🔹 GitHub Pages (автоматически подтягивает совместимые зависимости)
gem "github-pages", group: :jekyll_plugins

# 🔹 Дополнительные плагины
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jekyll-seo-tag"
end

# Ускорение работы Jekyll на Windows
platforms :mingw, :x64_mingw, :mswin do
  gem "wdm", "~> 0.1"
end
