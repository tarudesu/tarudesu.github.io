# Nguyen Thanh Luan — Academic Profile

Personal academic homepage for Nguyen Thanh Luan (Taru), focused on low-resource language technologies, machine translation, large language models, speech processing, and Vietnamese NLP.

Live site: [tarudesu.github.io](https://tarudesu.github.io/)

## What is included

- Home page with biography, research interests, linked news, and a persistent favorite-track player.
- Publications with TL;DR summaries, research-area filters, author emphasis, and Paper/Code/Dataset links.
- Experience page with research roles, project, honors, and academic service.
- Education page with degrees and thesis details.
- Responsive, dark-only interface with persistent navigation and accessible focus states.

## Stack

- Next.js 16, React 19, TypeScript
- vinext/Vite with Cloudflare Workers support
- Tailwind CSS 4 via PostCSS
- Lucide and React Icons

## Project structure

```text
app/
  components/       Shared shell, profile sidebar, navigation, and music player
  data.ts           News, publications, experience, and honors content
  page.tsx          Home page
  publications/     Filterable publications page
  experience/       Experience, honors, projects, and service page
  education/        Education page
  globals.css       Theme tokens, layout, responsive styles, and interactions
public/              Images and static assets
worker/               Cloudflare Worker entry point
db/                   Optional Drizzle/D1 database scaffold
examples/d1/          Optional D1 example
```

## Local development

Requires Node.js `>=22.13.0`.

```bash
npm install
npm run dev       # start the local site
npm run build     # create a production build
npm run lint      # run ESLint
```

Most profile content can be updated in `app/data.ts`; page structure lives beside each route in `app/`.

## GitHub Pages deployment

The site is exported as static HTML when `GITHUB_PAGES=true`:

```bash
GITHUB_PAGES=true npx next build
```

The generated site is written to `out/` and can be published to the `main` branch of the GitHub Pages repository. The repository also contains optional Cloudflare/D1 starter files, but the current public profile is static and does not require a database.
