# Orangery Ventures

A modern, fully responsive landing site for **Orangery Ventures** — a venture
studio / investment fund backing early-stage startup founders. The site
presents the fund's thesis, investment approach, the gap it fills for
founders, its community and media presence, and ways to connect.

## Features

- Hero section with animated intro and clear call-to-action
- "We got started 2025" about section with the fund's mission
- Thesis / Manifesto section explaining the investment philosophy
- "The Gap" — the problem the fund solves for founders in search
- Investment Approach breakdown
- Founders-in-search program spotlight
- Community and media section
- Connect / contact section + full footer
- Custom animations, serif display typography, dark elegant theme
- Client-side routing with 404 catch-all page

## Tech Stack

- **React 18** + **TypeScript**
- **Vite 5** (build tooling)
- **Tailwind CSS 3** + shadcn/ui component primitives (Radix UI)
- **React Router** (routing), **TanStack React Query**
- Recharts, React Hook Form + Zod, Framer-style custom animations
- Originally scaffolded with Lovable

## Quick Start

```bash
npm install
npm run dev        # local dev server on http://localhost:8080
```

## Build

```bash
npm run build      # outputs static files to dist/
npm run preview    # preview the production build locally
```

## Project Structure

```
.
├── index.html            # entry HTML (title: Orangery Ventures)
├── public/               # favicon, og-image, lovable-uploads
├── src/
│   ├── main.tsx          # app entry
│   ├── App.tsx           # providers + router
│   ├── pages/            # Index, NotFound
│   ├── components/       # Hero, About, Manifesto, Gap, InvestmentApproach,
│   │                     #   FoundersInSearch, Community, Connecting, Header, Footer
│   ├── components/ui/    # shadcn/ui primitives
│   ├── hooks/            # custom hooks
│   └── lib/              # utils
└── vite.config.ts
```

## Deploy Notes

Static Vite build (`dist/`) — deploys to any static host. This repo is
deployed via **GitHub Pages** (`gh-pages` branch, `dist/` contents, base path
`/Orangery-Ventures/`).

## License

Free for personal and commercial use.

---

Built by Girish Lade — https://ladestack.in
