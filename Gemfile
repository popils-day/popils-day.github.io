source "https://rubygems.org"

# Gem principal pour Jekyll
gem "jekyll", "~> 4.3.0"

# Thème par défaut (optionnel, peut être supprimé si style personnalisé)
gem "minima", "~> 2.5"

# Plugins essentiels pour GitHub Pages
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

# Compatibilité GitHub Pages
gem "github-pages", group: :jekyll_plugins

# Watcher pour Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock file pour compatibilité
gem "webrick", "~> 1.7"