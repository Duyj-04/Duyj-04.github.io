source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# NOTE: 这里不用 github-pages 元包——它锁定的 2021 版 gem（commonmarker 0.17 等）
# 在新版 Windows/MSVC 上编译不过。站点实际只用下面这几个插件（见 _config.yml）。
gem "jekyll"
gem "kramdown-parser-gfm"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jekyll-redirect-from"
  gem 'hawkins'
end

gem "webrick"
gem "tzinfo-data"
