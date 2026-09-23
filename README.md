# Olova

A small, static coming soon page for [olova.co](https://olova.co).

## Local development

```sh
npm ci
npm run dev
```

`npm run build` writes the production site to `dist/`. GitHub Actions checks the build on pushes and pull requests. Cloudflare Pages builds and deploys `main` automatically using `npm run build` and `dist`.
