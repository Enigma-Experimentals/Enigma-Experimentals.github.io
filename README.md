# Business Website Template

A modern business website template built for showcasing your company, products, and services.

```sh
pnpm install
pnpm dev
```

> 🚀 **Ready to customize?** Start by editing the content and styling to match your brand!

Features:

- ✅ Minimal styling (make it your own!)
- ✅ 100/100 Lighthouse performance
- ✅ SEO-friendly with canonical URLs and OpenGraph data
- ✅ Sitemap support
- ✅ RSS Feed support
- ✅ Markdown & MDX support

## 📁 Project Structure

Inside your project, you'll see the following folders and files:

```text
├── public/
├── src/
│   ├── components/
│   ├── content/
│   ├── layouts/
│   └── pages/
├── config.mjs
├── README.md
├── package.json
└── tsconfig.json
```

The `src/pages/` directory contains your website pages. Each file creates a route based on its filename.

The `src/components/` directory contains reusable components for your website.

The `src/content/` directory contains content collections for blog posts and other content. Use `getCollection()` to retrieve content and type-check your frontmatter using schemas.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm build`           | Build your production site to `./dist/`          |
| `pnpm preview`         | Preview your build locally, before deploying     |

## 👀 Want to learn more?

For documentation and support, please refer to the project documentation.

## Credit

This template is built on modern web technologies and follows best practices for performance and accessibility.
