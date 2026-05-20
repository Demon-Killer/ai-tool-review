# AI Tool Radar

> Honest, in-depth reviews and comparisons of the best AI tools in 2026.

## About

AI Tool Radar is a static website built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme. We test AI tools hands-on and publish honest reviews with real benchmarks and data.

## Tech Stack

- **Static Site Generator**: Hugo v0.161.1
- **Theme**: PaperMod
- **Hosting**: Cloudflare Pages (free)
- **Analytics**: Google Analytics
- **Monetization**: Google AdSense

## Site

Live at [ai-tool-review.pages.dev](https://ai-tool-review.pages.dev/)

## Project Structure

```
content/
├── posts/          # AI tool review articles
├── about.md        # About page
├── contact.md      # Contact page
├── privacy-policy.md
├── terms-of-service.md
└── disclaimer.md

layouts/
└── partials/
    └── extend_head.html  # Google verification + AdSense

assets/
└── css/
    └── extended/
        └── custom.css     # Custom styling

static/
├── ads.txt          # AdSense ads.txt
└── robots.txt       # Search engine directives
```

## Development

```bash
# Install Hugo (Windows)
winget install Hugo.Hugo.Extended

# Local development
hugo server -D

# Build
hugo

# Deploy
git push  # Cloudflare Pages auto-deploys from GitHub
```
