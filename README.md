# mariomiralles.com

Personal portfolio site for **Mario Miralles** — Fullstack Engineer, WordPress Developer, and Claude Code Engineer based in South Florida.

**[mariomiralles.com](https://mariomiralles.com)**

---

## What This Is

A single-page portfolio built from scratch with vanilla HTML, CSS, and JavaScript. No frameworks, no build tools, no dependencies — just clean, hand-crafted code with a focus on performance and visual polish.

## Highlights

- **Flow field canvas** — Procedural particle system reacting to scroll position and mouse proximity, rendered on a fixed canvas behind all content
- **Live GitHub contributions** — Fetches real contribution data and renders a heatmap grid with hover tooltips
- **Parallax scroll transitions** — Sections reveal with staggered animations as they enter the viewport via Intersection Observer
- **Glass morphism design** — Frosted glass cards, subtle glow tracking on hover, and a cohesive dark theme built on CSS custom properties
- **Zero dependencies** — Everything is in a single `index.html` file. No npm, no bundler, no framework

## Tech Stack

| Layer | Tech |
|-------|------|
| Markup | Semantic HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, backdrop-filter) |
| Interactivity | Vanilla JavaScript (Intersection Observer, Canvas API, Fetch API) |
| Fonts | [Sora](https://fonts.google.com/specimen/Sora) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts |
| Hosting | GitHub Pages |
| Domain | Custom domain via CNAME |

## Run Locally

```bash
# Clone it
git clone https://github.com/mariomiralles/mario-miralles.git
cd mario-miralles

# Serve it (any static server works)
npx http-server -p 8080
```

Open `http://localhost:8080` and you're in.

## Project Structure

```
mario-miralles/
├── index.html    # Everything — markup, styles, scripts
├── CNAME         # Custom domain for GitHub Pages
└── README.md
```

Yes, it's one file. That's the point.

## About Me

I've built 100+ websites across healthcare, legal, home services, towing, and tech. I specialize in WordPress development, custom plugin building, and AI-powered development with Claude Code.

Currently building [SiteStaffr](https://sitestaffr.com) — an AI voice agent WordPress plugin that captures leads through natural conversation in 57+ languages.

- [LinkedIn](https://www.linkedin.com/in/mariofmiralles)
- [GitHub](https://github.com/mariomiralles)
- [Email](mailto:miralles.mario@gmail.com)

---

Built with [Claude Code](https://claude.ai/claude-code)
