# Gemfile for TCM_JTD Just the Docs Website
# This file manages Ruby gem dependencies for the Jekyll-based documentation site.

source "https://rubygems.org"

# Standard Ruby libraries for data handling and time zones.
gem 'csv'                # For CSV file parsing and generation
gem 'base64'             # For Base64 encoding/decoding
gem 'bigdecimal'         # For high-precision decimal arithmetic
gem 'tzinfo'             # Timezone support
gem 'tzinfo-data'        # Timezone data for Windows

# --- Web Server for Local Development ---
gem "webrick"            # Required for Jekyll on Windows (Ruby 3+)

# --- Markdown Parsing ---
gem 'kramdown-parser-gfm' # GitHub Flavored Markdown support

# --- Jekyll and Core Plugins ---
gem 'jekyll'             # Static site generator

# --- SASS/SCSS Support ---
gem 'jekyll-sass-converter' # For custom stylesheets

# --- SEO and Metadata ---
gem 'jekyll-seo-tag'     # SEO tags for better search engine visibility

# --- Theme and Layout Support ---
gem 'jekyll-remote-theme'    # Use remote themes from GitHub
gem 'jekyll-github-metadata' # GitHub metadata for Jekyll sites hosted on GitHub Pages
gem 'jekyll-default-layout'  # Default layout support for Jekyll

# --- Optional Jekyll Themes ---
gem 'jekyll-theme-hacker'    # Optional: Hacker theme (remove if unused)
gem 'jekyll-theme-primer'    # Optional: Primer theme (remove if unused)

# --- Windows Compatibility ---
gem 'wdm', '>= 0.1.0' if Gem.win_platform? # File system event monitoring for auto-regeneration

# --- Main Site Theme ---
gem 'just-the-docs', '~> 0.10.1' # Main documentation theme