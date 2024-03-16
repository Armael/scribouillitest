source "https://rubygems.org"

gem "jekyll", "~> 4.3.2"

# Jekyll theme for Scribouilli
gem "mimoza", git: "https://github.com/Scribouilli/mimoza.git", branch: "main"

group :jekyll_plugins do
  # Handle redirections
  gem "jekyll-redirect-from", "~> 0.16"

  # Atom feed on Jekyll posts
  gem "jekyll-feed", "~> 0.17"

  # Pagination
  gem "jekyll-paginate-v2", "~> 3.0"

  # SEO tags
  gem "jekyll-seo-tag", "~> 2.8"

  # Generate a sitemap
  gem "jekyll-sitemap", "~> 1.4"

  # Enable Jekyll to read custom YAML front matter
  gem "jekyll-optional-front-matter", "~> 0.3"

  # Add default layouts to pages and posts
  gem "jekyll-default-layout", "~> 0.1.5"

  # Generate default titles from headings
  gem "jekyll-titles-from-headings", "~> 0.5.3"
end

group :development do
  gem "dotenv", "~> 2.7"
  gem "webrick", "~> 1.7"
end

group :test do
  gem 'rspec'
end
