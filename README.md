# Paolo Magalini's Personal Website

This is a work in progress Jekyll site hosted on GitHub Pages.

## Local Development

### Prerequisites
- Ruby 3.2+
- Bundler

### Setup

1. Install dependencies:
```bash
bundle install
```

2. Build the site:
```bash
bundle exec jekyll build
```

3. Serve locally:
```bash
bundle exec jekyll serve
```

Visit `http://localhost:4000` to view the site.

## Structure

- `_config.yml` - Jekyll configuration
- `_layouts/` - Page templates
- `_posts/` - Blog posts (YYYY-MM-DD-title.md format)
- `_includes/` - Reusable components
- `assets/` - CSS, images, and other static files
- `index.md` - Homepage
- `about.md` - About page

## Adding Content

### New Blog Post
Create a new file in `_posts/` with the format: `YYYY-MM-DD-title.md`

```markdown
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS +0000
categories: category1 category2
---

Your content here...
```

### New Page
Create a new `.md` file in the root directory:

```markdown
---
layout: default
title: Page Title
permalink: /page-url/
---

Your content here...
```

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the main branch.
