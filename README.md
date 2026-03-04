# 出口成帳（Money Talks）官網

Official landing page for **出口成帳（Money Talks）** built with **React + Vite**.

## Tech Stack

- React 18
- Vite 5
- CSS (single stylesheet: `src/styles.css`)
- Vercel Analytics (`@vercel/analytics`)

## Project Structure

```text
.
├── index.html
├── package.json
├── vite.config.js
├── src/
│   ├── main.jsx
│   ├── App.jsx
│   └── styles.css
├── public/
│   ├── icon.png
│   ├── app_store_icon.png
│   ├── screenshot.png
│   ├── 0304.mp4
│   ├── robots.txt
│   └── sitemap.xml
├── robots.txt
└── sitemap.xml
```

## Getting Started

### 1. Install dependencies

```bash
npm install
```

### 2. Run development server

```bash
npm run dev
```

Vite will print a local URL (usually `http://localhost:5173`).

### 3. Build for production

```bash
npm run build
```

### 4. Preview production build

```bash
npm run preview
```

## NPM Scripts

- `npm run dev` - Start local development server
- `npm run build` - Build production assets into `dist/`
- `npm run preview` - Preview built site locally

## Content & UI Editing

- Main page content/layout: `src/App.jsx`
- Global styles: `src/styles.css`
- HTML meta, title, favicon, root mount: `index.html`

## Assets

Hero and brand assets are served from `public/`:

- App icon: `public/icon.png`
- App Store icon: `public/app_store_icon.png`
- Hero video: `public/0304.mp4`
- Hero poster fallback: `public/screenshot.png`

## SEO Files

- `public/robots.txt`
- `public/sitemap.xml`

If you update domain or routes, update sitemap/robots accordingly.

## Analytics

Vercel Analytics is enabled via `<Analytics />` in `src/App.jsx`.

## Deployment

Recommended deployment: **Vercel**.

Default Vite settings are already compatible:

- Build command: `npm run build`
- Output directory: `dist`

## Legal / Support Links

Configured in footer (`src/App.jsx`):

- Privacy Policy
- Terms of Use
- Customer Support
