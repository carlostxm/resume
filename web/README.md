# Astro Starter Kit: Blog

```sh
npm create astro@latest -- --template blog
```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

Features:

- ✅ Minimal styling (make it your own!)
- ✅ 100/100 Lighthouse performance
- ✅ SEO-friendly with canonical URLs and OpenGraph data
- ✅ Sitemap support
- ✅ RSS Feed support
- ✅ Markdown & MDX support

````markdown
# CV site

Single-page Astro site that renders `src/CV.md` as the homepage. Styling and meta tags are provided through shared components, and a sitemap is generated for deployment.

## Structure

```text
├── public/
├── src/
│   ├── components/   # BaseHead, Footer
│   ├── pages/        # index.astro (renders the CV)
│   ├── styles/       # global styles
│   └── CV.md         # markdown CV content
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## Commands

| Command           | Action                                     |
| :---------------- | :----------------------------------------- |
| `npm install`     | Install dependencies                       |
| `npm run dev`     | Start local dev server at `localhost:4321` |
| `npm run build`   | Build the production site to `./dist/`     |
| `npm run preview` | Preview the production build locally       |

## Notes

- The page pulls CV content from `src/CV.md` at build time using `marked`.
- Meta tags and global CSS are set via `BaseHead`.
- Sitemap generation remains enabled via `@astrojs/sitemap`.
````

| `npm run preview` | Preview your build locally, before deploying |
