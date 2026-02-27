# Visions on the Path

**Live Site:** [https://visionsonthepath.com](https://visionsonthepath.com)

A personal website dedicated to sharing insights, mantras, and resources related to Kriya Yoga, meditation, and spiritual practice.

## About

Visions on the Path is a spiritual resource website featuring:

- **Mantras** - A comprehensive collection of Sanskrit mantras with translations, transliterations, definitions, and commentary
- **Resources** - Curated books, websites, and teachers related to Kriya Yoga and spiritual practice
- **About** - Personal journey and background in Kriya Yoga practice
- **Daily Verse** - Daily spiritual wisdom and reflection

## Technology

This site is built with:

- **[Astro](https://astro.build)** - Static site generator
- **GitHub Pages** - Hosting and deployment
- **GitHub Actions** - Automated deployment pipeline

## Development

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or pnpm

### Getting Started

1. Clone the repository:
```bash
git clone https://github.com/bodhi-root/votp-website.git
cd votp-website
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The site will be available at `http://localhost:4321`

### Available Commands

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build production site to `./dist/` |
| `npm run preview` | Preview production build locally |

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `master` branch. The deployment workflow is configured in [.github/workflows/deploy.yml](.github/workflows/deploy.yml).

## Project Structure

```
/
├── public/              # Static assets
│   ├── images/         # Images and icons
│   └── favicon.png     # Site favicon
├── src/
│   ├── components/     # Reusable Astro components
│   │   ├── Panel.astro
│   │   ├── Mantra.astro
│   │   ├── LinkItem.astro
│   │   └── ...
│   ├── layouts/        # Page layouts
│   │   └── BaseLayout.astro
│   ├── pages/          # Page routes
│   │   ├── index.astro
│   │   ├── mantras.astro
│   │   ├── resources.astro
│   │   └── about.astro
│   └── styles/         # Global styles
│       └── global.css
└── astro.config.mjs    # Astro configuration
```

## License

This project is a personal website. Content is copyrighted by the author. Code may be referenced for educational purposes.
