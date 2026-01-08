# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Common Commands

The following scripts are available in package.json:

- `dev`: Runs `astro dev` to start the development server at localhost:4321
- `build`: Runs `astro build` to build the production site to `./dist/`
- `preview`: Runs `astro preview` to preview the built site locally
- `astro`: Access Astro CLI commands (e.g., `astro add`, `astro check`)

Note: This project currently doesn't include dedicated linting or testing scripts. You may want to add these depending on your needs.

## Architecture Overview
This is a modern business website template. Key structural elements:

- **src/pages/** - Contains pages that define routes (homepage, blog posts, etc.)
- **src/components/** - Reusable components (Header, Footer, BlogPost layout)
- **src/content/** - Content collections with Markdown/MDX blog posts and documentation
- **public/** - Static assets like images, fonts, and favicon
- **config.mjs** - Configuration with integrated plugins for MDX, RSS, and sitemap

Key features included:
- SEO optimization with canonical URLs and OpenGraph data
- Automated RSS feed generation
- Sitemap support
- Markdown and MDX content support with syntax highlighting
- 100/100 Lighthouse performance score

The project follows content collections pattern for managing blog posts, allowing type-safe frontmatter validation through optional schemas.