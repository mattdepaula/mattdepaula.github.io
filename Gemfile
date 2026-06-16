source "https://rubygems.org"

# GitHub Pages build environment (Jekyll + supported plugins).
gem "github-pages", group: :jekyll_plugins

# Plugins used by the Minimal Mistakes remote theme.
group :jekyll_plugins do
  gem "jekyll-remote-theme"
  gem "jekyll-include-cache"
end

# Windows/JRuby tzinfo support (harmless elsewhere).
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
