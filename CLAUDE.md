# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Language and Communication Guidelines

- **默认使用中文回答**: 除非用户明确要求使用英文，否则请始终使用中文与用户交流
- **默认使用中文注释**: 在编写代码时，所有注释均使用中文，包括代码块中的注释和说明文本

## Project Overview

This is an Academic Pages Jekyll website, a GitHub Pages template for personal academic portfolio websites. It's built using Jekyll and hosted on GitHub Pages.

## Development Commands

### Local Development
```bash
# Install Ruby dependencies
bundle install

# If permission errors occur, install gems locally
bundle config set --local path 'vendor/bundle'
bundle install

# Serve locally for development (auto-reload on changes)
jekyll serve -l -H localhost
# Alternative if bundle path is configured
bundle exec jekyll serve -l -H localhost
```

### Docker Development
```bash
# Build and run using Docker
docker compose up
```

### JavaScript Build Process
```bash
# Build minified JavaScript from dependencies and source files
npm run build:js
# or specifically:
npm run uglify

# Watch JavaScript files and rebuild on changes
npm run watch:js
```

## Site Architecture

### Jekyll Collections
The site uses Jekyll collections for content organization:
- `_posts/` - Blog posts
- `_publications/` - Academic publications
- `_talks/` - Conference talks and presentations
- `_teaching/` - Teaching experience
- `_portfolio/` - Portfolio items
- `_pages/` - Static pages (About, CV, etc.)

### Key Configuration Files
- `_config.yml` - Main Jekyll configuration
- `_config_docker.yml` - Docker-specific configuration
- `Gemfile` - Ruby dependencies
- `package.json` - JavaScript dependencies and build scripts

### Content Structure
- Author information and social links configured in `_config.yml` under the `author:` section
- Navigation defined in `_data/navigation.yml`
- Site text and UI strings in `_data/ui-text.yml`

### Layout System
- `_layouts/` contains page templates
- `_includes/` contains reusable components
- `_sass/` contains stylesheet partials
- `assets/` contains compiled assets and media files

### Static Files
- `images/` - Profile photos and site images
- `files/` - PDFs and downloadable content (papers, slides, CV)

## Content Management

### Adding Publications
Create markdown files in `_publications/` with front matter including title, authors, venue, date, and publication type (preprints, manuscripts, conferences).

### Adding Talks
Create markdown files in `_talks/` with front matter for talk details, venue, and date.

### Python Generators
The `markdown_generator/` directory contains Jupyter notebooks and Python scripts to automatically generate markdown files from TSV data:
- `publications.py` - Generate publication pages from `publications.tsv`
- `talks.py` - Generate talk pages from `talks.tsv`

## Customization Areas

### Author Profile
Update personal information, social media links, and contact details in `_config.yml` under the `author:` section.

### Site Theme
The site uses a custom academic theme based on Minimal Mistakes Jekyll theme. Styling can be customized in `_sass/` directories.

### Analytics and SEO
Configure Google Analytics, social media meta tags, and site verification in `_config.yml`.