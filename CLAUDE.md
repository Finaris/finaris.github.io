# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a Jekyll-powered personal website and blog hosted on GitHub Pages. The site uses the Slate theme and serves as Madelyn's personal portfolio and blog site at madelyn.dev.

## Development Commands

### Local Development
```bash
# Install dependencies
bundle install

# Serve the site locally with live reload
bundle exec jekyll serve

# Build the site
bundle exec jekyll build
```

### Jekyll Commands
- `bundle exec jekyll serve --drafts` - Include draft posts in local development
- `bundle exec jekyll serve --incremental` - Enable incremental rebuilds for faster development
- `bundle exec jekyll clean` - Clean the build directory

## Architecture

### Site Structure
- `_config.yml` - Main Jekyll configuration, site metadata, and theme settings
- `_layouts/` - HTML templates for different page types (default, home, post)
- `_includes/` - Reusable HTML components (footer, head-custom, social)
- `_posts/` - Blog posts in Markdown format with YAML front matter
- `_sass/` - SCSS styling files
- `assets/` - Static assets including CSS, images, and favicon files

### Content Organization
- Blog posts follow naming convention: `YYYY-MM-DD-title.md`
- Post front matter includes layout, title, categories, and optional thumbnail_image
- Images are organized in `/assets/posts/[post-slug]/` directories
- Categories are used for post organization (Personal, Conferences, etc.)

### Theme and Styling
- Uses `pages-themes/slate` remote theme via GitHub Pages
- Custom styles in `/assets/css/styles.scss` override theme defaults
- Social media links configured in `_config.yml` under `social_media_links`

### Key Files
- `blog.html` - Blog listing page
- `categories.html` - Posts organized by category
- `about.md` - Personal bio and contact information
- `index.html` - Homepage

## GitHub Pages Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the main branch. No manual build or deployment steps are required.