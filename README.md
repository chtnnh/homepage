# Chaitanya Mittal — Homepage

An editorial solarpunk portfolio built with Astro and deployed as a static site.

## Commands

```sh
npm install
npm run dev
npm run build
npm run preview
```

The site follows the visitor's system color preference and includes a persistent
manual theme toggle. Motion is disabled when `prefers-reduced-motion` is active.

## Deployment

Push the `main` branch to GitHub. The workflow in `.github/workflows/deploy.yml`
builds and deploys the site to GitHub Pages.

The custom domain is configured through `public/CNAME` as
`me.chtnnhfoundation.org`. Point the corresponding Cloudflare DNS record to the
GitHub Pages site before enabling the custom domain in repository settings.
