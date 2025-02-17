
source "https://rubygems.org"

# Основной движок Jekyll
gem "jekyll", "~> 4.4.1"

# Тема (можно заменить)
gem "minima", "~> 2.5"

# 🔹 Плагины Jekyll
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"        # Генерирует RSS-фид
  gem "jekyll-sitemap"                # Создает sitemap.xml для SEO
  gem "jekyll-paginate"               # Добавляет пагинацию
  gem "jekyll-seo-tag"                # SEO-оптимизация
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
