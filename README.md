# AETH — Built for the AI Era

An intelligent website platform designed for the post-search internet. AETH helps founders build web presences that work simultaneously for human visitors, AI systems, and search engines.

**Live:** [aeth.vercel.app](https://aeth.vercel.app) · **Repo:** [github.com/mksvlbv/aeth](https://github.com/mksvlbv/aeth)

## Overview

AETH is a full-stack product concept and MVP demonstrating a modern SaaS landing site with a functional dashboard. Built as a portfolio piece showcasing frontend engineering, product design, and UI/UX thinking.

## Tech Stack

- **Framework:** Next.js 16 (App Router, React 19)
- **Styling:** Tailwind CSS v4
- **Animations:** Framer Motion (scroll-triggered fade-ins)
- **Typography:** Inter + IBM Plex Mono
- **Icons:** Lucide React
- **Deploy:** Vercel

## Pages (20 routes)

| Page | Description |
|------|-------------|
| `/` | Homepage — hero with monolith visual, 9 content sections, scroll animations |
| `/features` | Product architecture — 5-layer system stack |
| `/how-it-works` | 4-step process with live metrics |
| `/pricing` | 3-tier pricing (Starter, Pro, Enterprise) |
| `/about` | Origin story, mission, values |
| `/blog` | 6 article cards, 2 with full content |
| `/blog/[slug]` | Dynamic blog post pages |
| `/changelog` | Version history with release notes |
| `/contact` | Book a Demo form |
| `/login` | Auth screen with demo skip |
| `/dashboard` | System overview — 7 HUD widgets, live clock |
| `/dashboard/editor` | Visual block editor with AI assistant |
| `/dashboard/settings` | Account, site config, notifications |
| `/privacy` | Privacy policy |
| `/terms` | Terms of service |
| `/not-found` | Branded 404 page |

## Design DNA

- Dark theme: `#050505` background, `#00F0FF` cyan accent, `#FF2D55` red accent
- Monospace system labels and data points
- Subtle grid overlay background
- Card hover micro-interactions (cyan glow + lift)
- Responsive: mobile-first, tested at 375px and 1440px

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Build

```bash
npm run build
npm start
```

## Author

**Maksym Volobuiev** — [GitHub](https://github.com/mksvlbv)
