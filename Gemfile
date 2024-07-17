source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
gem "jekyll" #, "~> 4.1.1"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins

# This is the default theme for new Jekyll sites. You may change this to anything you like.
# gem "minima" #, "~> 2.5"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed"# , "~> 0.12"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo"# , "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", :platforms => [:mingw, :x64_mingw, :mswin] # "~> 0.1.1",

## Code Syntax Highlighter ##
# CSS from https://github.com/richleland/pygments-css.git
gem 'rouge' # 3.26.0

## Explicitly Required for Ruby 3.0 ##
gem 'webrick'  # 1.7.0

## Gem for Nesting Yamls excellent for double configs
gem 'yaml_extend'
