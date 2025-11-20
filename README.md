# Carlos Torres Martínez - Resume

Professional resume and portfolio site.

## 📄 CV

The resume is available in Markdown format: [CV.md](./CV.md)

## 🌐 Web Version

Interactive web version built with [Astro](https://astro.build/) deployed on [Vercel](https://vercel.com).

### Development

```bash
cd web
npm install
npm run dev
```

Visit `http://localhost:4321` to see the site.

### Architecture

- **Single Source of Truth**: The web reads directly from `CV.md` in the repository root
- **Zero Duplication**: No content is duplicated between the markdown file and web version
- **Static Generation**: Full HTML generated at build time for optimal performance
- **Minimal JS**: Zero JavaScript shipped to the browser by default

### Deployment

- **Production**: Automatically deployed to Vercel on merge to `main`
- **Preview**: Each PR gets its own preview URL for review

#### Setup Vercel Deployment

1. Connect your GitHub repository to Vercel
2. Configure the following secrets in GitHub:

   - `VERCEL_TOKEN`: Your Vercel token
   - `VERCEL_ORG_ID`: Your Vercel organization ID
   - `VERCEL_PROJECT_ID`: Your Vercel project ID

3. Vercel will automatically:
   - Deploy previews on every PR
   - Deploy to production on merge to `main`

## 🛠️ Tech Stack

### Web

- **Framework**: Astro 5
- **Styling**: Custom CSS with CSS Variables
- **Markdown**: marked
- **TypeScript**: Strict mode
- **Deployment**: Vercel

## 📝 License

© 2025 Carlos Torres Martínez
