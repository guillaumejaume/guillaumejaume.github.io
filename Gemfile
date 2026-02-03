source "https://rubygems.org"

# Gemfile for local Jekyll development

ruby ">= 3.2.0"

# Core Jekyll
gem "jekyll", "~> 4.3"
# Use sassc instead of sass-embedded (avoids google-protobuf/rake native build issues)
gem "jekyll-sass-converter", "~> 2.0"

# Plugins used by this site (see _config.yml :plugins)
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jekyll-gist"
  gem "jekyll-redirect-from"
end

# Needed for Ruby 3.4+ / 4.0+ where some stdlib gems
# (like csv and bigdecimal) are no longer bundled by default.
gem "csv"
gem "bigdecimal"

