# ashiskar.github.io

Personal portfolio website built with Jekyll and hosted on GitHub Pages.

## Design Philosophy

This site embodies a minimalist, "deep work" aesthetic:
- **Dark mode** by default (implies focus and depth)
- **Serif fonts** for headings (Georgia) — evokes a reader/thinker vibe
- **Sans-serif** for body text — clean and readable
- **Plenty of whitespace** — lets content breathe
- **Quiet confidence** — showcasing achievements without arrogance

## Structure

```
├── _config.yml           # Jekyll configuration
├── _layouts/             # Custom HTML layouts
│   ├── default.html      # Base layout
│   └── post.html         # Blog post layout
├── _includes/            # Reusable HTML snippets
│   └── head-custom.html  # Custom head content
├── _posts/               # Blog posts (Jekyll convention)
├── assets/
│   └── style.css         # Main stylesheet (dark mode)
├── index.md              # Home page
├── about.md              # Notes/About page
└── README.md             # This file
```

## Running Locally

### Prerequisites
- Ruby 2.7+ (recommend using rbenv or rvm)
- Bundler

### Setup & Run

```bash
# Install dependencies
bundle install

# Serve locally with live reload
bundle exec jekyll serve --livereload

# Open http://localhost:4000
```

### Troubleshooting

If you encounter gem installation issues (especially on macOS):

```bash
# Use Homebrew Ruby instead of system Ruby
brew install rbenv ruby-build
rbenv install 3.1.4
rbenv global 3.1.4

# Reinstall bundler and gems
gem install bundler
bundle install
```

## Deployment

This site is automatically deployed to GitHub Pages when you push to the `main` branch. No additional configuration needed.

**Live URL:** https://ashiskar.me

## Content Sections

### Home Page (`index.md`)
1. **Hero** — Headline and introduction
2. **Philosophy** — "How I Think" section
3. **Scale** — Metrics and impact
4. **Curiosity** — Current explorations and reading list
5. **Footer** — Contact links

### About/Notes Page (`about.md`)
- Space for deeper essays and technical writing
- Blog post listing
- Contact information

## Customization

### Colors
Edit CSS variables in `assets/style.css`:

```css
:root {
  --bg-primary: #0a0a0a;      /* Main background */
  --bg-secondary: #141414;    /* Card/section backgrounds */
  --text-primary: #e8e8e8;    /* Main text */
  --text-secondary: #a0a0a0;  /* Secondary text */
  --text-muted: #707070;      /* Muted text */
  --accent: #ffffff;          /* Accent/highlight */
  --border: #2a2a2a;          /* Borders */
}
```

### Fonts
- Headings: Georgia (serif)
- Body: System font stack (San Francisco on macOS, Segoe UI on Windows)

### Adding Blog Posts
Create a new file in `_posts/` following Jekyll's naming convention:

```
YYYY-MM-DD-title-slug.md
```

Example:
```markdown
---
layout: post
title: "Building Resilient Systems"
date: 2025-12-10 10:00:00 +0530
categories: blog systems
---

Your content here...
```

## License

Content © Ashis Kar. Code MIT licensed.
Personal learning blogs
