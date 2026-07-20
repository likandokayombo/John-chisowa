This project is heavily influenced and inspired by [David Umoru](https://davidumoru.me/).


***This project is still in deveploment***

## Tech Stack

- **Framework** — [Astro](https://astro.build/) v7.1.2
- **Content** — MDX via `@astrojs/mdx` v7.0.3
- **Syntax highlighting** — `astro-expressive-code` v0.44.1 (Rose Pine Dawn light / Kanagawa Dragon dark)
- **Typography** — Editorial New (self-hosted) + Inter (Google Fonts)
- **Colors** — OKLCH (Tomato accent + Gray palette)
- **Package manager** — pnpm

## Folder Structure

```
src/
├── content/
│   ├── content.config.ts          # Content collections config
│   └── blog/
│       ├── design-system.mdx      # Blog post about the design system
│       └── hello-world.mdx        # First blog post
├── layouts/
│   ├── BlogLayout.astro           # Blog post layout
│   └── Layout.astro               # Base HTML layout
├── pages/
│   ├── index.astro                # Homepage (lists blog posts)
│   └── blog/
│       ├── [slug].astro           # Dynamic blog post route
│       └── index.astro            # Blog listing page
└── styles/
    └── global.css                 # Global styles, fonts, colors

public/
└── fonts/
    └── editorial-new/             # Self-hosted Editorial New font files
```
