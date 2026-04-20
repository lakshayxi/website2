# Lakshay Saini Portfolio

A minimalist, brutalist portfolio website built with Astro 4.x. This project focuses on high performance, static generation, and a clean monospace aesthetic to showcase ML research and engineering projects.

## Tech Stack

* Framework: Astro 4.x (Static output)
* Styling: Plain CSS
* Fonts: IBM Plex Mono (Weights 400 and 600)
* Deployment: GitHub Pages

## Architecture

The site is designed as a single column, left aligned document. It follows a modular structure where sections like Research, Projects, and Experience are built as independent Astro components. All styling is centralized in a global CSS file using tokens for consistent spacing and typography.

## Local Development

Prerequisites: Node.js 20 or higher.

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open http://localhost:4321 in your browser.

## Build and Deployment

To generate the static site manually:

```bash
npm run build
```

The output will be located in the `dist/` directory. Deployment is automated via GitHub Actions on every push to the main branch.

## License

MIT
