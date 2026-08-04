# Gemfile

source 'https://rubygems.org'
ruby '3.0.2'

# Other gem dependencies
gem 'jekyll', '~> 4.2.0'
gem 'kramdown', '~> 2.5.1'
# Pinned exactly: the deploy workflow pre-installs this same version, and a
# looser constraint lets `bundle update` drift to a newer uri than the one
# already activated, which aborts `bundle exec jekyll`.
gem 'uri', '1.0.3'

# Add other gems as necessary
group :jekyll_plugins do
    gem 'classifier-reborn'
    gem 'jekyll-archives'
    gem 'jekyll-email-protect'
    gem 'jekyll-feed'
    gem 'jekyll-get-json'
    gem 'jekyll-imagemagick'
    gem 'jekyll-jupyter-notebook'
    gem 'jekyll-link-attributes'
    gem 'jekyll-minifier'
    gem 'jekyll-paginate-v2'
    gem 'jekyll-scholar'
    gem 'jekyll-sitemap'
    gem 'jekyll-toc'
    gem 'jekyll-twitter-plugin'
    gem 'jemoji'
    gem 'mini_racer'
    gem 'unicode_utils'
    gem 'webrick'
end
group :other_plugins do
    gem 'feedjira'
    gem 'httparty'
end
