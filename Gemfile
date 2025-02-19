source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins  # Используем версию, поддерживаемую GitHub Pages
gem "jekyll", "~> 4.4.1"                    # Основной движок Jekyll
gem "jekyll-theme-hacker"                   # Указанная тема
gem "minima", "~> 2.5"                       # Тема Minima (можно удалить, если не нужна)

# 🔹 Дополнительные плагины Jekyll
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"        # RSS-фид
  gem "jekyll-sitemap"                # Sitemap.xml
  gem "jekyll-paginate"               # Пагинация
  gem "jekyll-seo-tag"                # SEO-оптимизация
  gem "jekyll-remote-theme"            # Позволяет использовать `remote_theme`
end

# Поддержка часовых зон на Windows
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Ускорение работы Jekyll на Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Поддержка HTTP в JRuby
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
