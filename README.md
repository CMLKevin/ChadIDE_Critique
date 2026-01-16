# The Anatomy of UX Failure: Chad IDE

A comprehensive critical analysis of Chad IDE's user experience failures, deployed on Cloudflare Pages.

## About This Project

This is an editorial-style blog post that systematically analyzes the UX problems with Chad IDE, the Y Combinator-backed "brainrot IDE" that embeds social media, gambling, dating apps, and minigames directly into a code editor.

The analysis covers:

- **Nielsen's 10 Heuristics** — All 10 violated
- **Cognitive Science** — Fitts's Law, Hick's Law, Cognitive Load Theory, Gestalt Principles
- **Mental Model Violations** — Breaking established IDE conventions
- **Dark Patterns** — Ethical concerns with gambling integration
- **Accessibility Failures** — WCAG compliance issues
- **The Wasted Potential** — Better alternatives for AI wait times

## Deployment

This site is deployed on [Cloudflare Pages](https://pages.cloudflare.com/).

### Deploy Your Own

1. Fork this repository
2. Connect to Cloudflare Pages
3. Set build configuration:
   - **Build command:** (leave empty - static site)
   - **Build output directory:** `/`
4. Deploy

### Local Development

Simply open `index.html` in a browser. No build step required.

```bash
open index.html
```

## Project Structure

```
├── index.html      # Main blog post
├── 404.html        # Custom 404 page
├── _headers        # Cloudflare security headers
├── _redirects      # Cloudflare redirects
└── README.md       # This file
```

## Tech Stack

- Pure HTML/CSS/JS (no framework)
- Google Fonts (Playfair Display, Source Serif 4, JetBrains Mono, Archivo)
- Intersection Observer API for scroll animations
- CSS Custom Properties for theming

## License

MIT License - Feel free to use this as a template for your own design critiques.

---

*"Unlike Chad IDE, we actually care about user experience."*
