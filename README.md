# sosProjectsWeb

Static website for SOS Projects.

## Deployment

This project is ready to deploy to [Vercel](https://vercel.com/).

1. Install the Vercel CLI if you do not already have it:

   ```bash
   npm install -g vercel
   ```

2. Build the site locally to verify the deployment:

   ```bash
   npx vercel build
   ```

3. Deploy to Vercel:

   ```bash
   npx vercel --prod
   ```

The included `vercel.json` configuration rewrites all routes to `index.html` so the static site works for any path.
