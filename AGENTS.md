# AGENTS.md - Cosmic Ecology Development Guide

## Commands

- **Build**: `zola build` - Builds the static site
- **Serve**: `zola serve` - Development server with hot reload
- **Check**: `zola check` - Validates content and links
- **Deploy**: Netlify auto-deploys from git pushes to main

## Architecture

- **Framework**: Zola static site generator (v0.18.0)
- **Content**: Markdown files in `content/` with TOML frontmatter
- **Templates**: Tera templates in `templates/`
- **Static Assets**: Files in `static/` copied to `public/`
- **Styling**: Sass files in `sass/` (compile_sass = false in config)
- **Deployment**: Netlify hosting with custom domain

## Content Structure

- `content/_index.md`: Homepage content
- `content/chapters/`: Book chapters with individual markdown files
- Frontmatter uses `+++` delimiters with TOML syntax

## Style Guidelines

- Use descriptive filenames and keep content organized by type
- Markdown content should be well-structured with proper headings
- Templates follow Tera syntax for variables and filters
- Static assets go in `static/` directory for direct copying
