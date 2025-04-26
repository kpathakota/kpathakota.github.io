# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Build Commands
- `bundle exec jekyll serve` - Run local development server
- `bundle exec jekyll build` - Build site for production
- `bundle install` - Install dependencies

## Code Style Guidelines
- **Jekyll/Liquid Templates**: Follow standard Liquid syntax
- **Markdown**: Use GitHub Flavored Markdown
- **Front Matter**: Include layout, title, date, categories, and tags
- **File Naming**: For posts, use `YYYY-MM-DD-title-slug.md`
- **Images**: Place in `assets/images/` with descriptive filenames
- **PDFs**: Store in `assets/pdf/`
- **Layouts**: Utilize Minimal Mistakes theme conventions
- **HTML**: Minimize custom HTML, prefer markdown when possible

## Navigation
- Configure navigation in `_data/navigation.yml`
- Pages should be placed in `_pages/` directory
- Blog posts belong in `_posts/` directory