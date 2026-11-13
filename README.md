# SHAYAN — Portfolio

A Vercel-ready static portfolio with separate HTML, CSS and JavaScript files. The browser-tab icon is `public/favicon.svg` (a custom S mark, not a stock photo).

## Preview locally

Open `index.html` in your browser. No Node.js or build step is required. Google Fonts load over the internet; fallback fonts are included.

## Deploy to Vercel

1. Extract this ZIP.
2. Create a new GitHub repository and upload the contents of this folder (keep `index.html`, `style.css`, `script.js`, `vercel.json`, and `public/` at the repository root).
3. In Vercel, choose **Add New → Project**, import that GitHub repository, and deploy.
4. Framework Preset: **Other**. Build Command: leave empty. Output Directory: `.`. Install Command: leave empty.

You can also use the Vercel CLI from this folder: `npx vercel` and follow its prompts.

## Personalize

- In `index.html`, replace `YOUR_EMAIL@example.com` with your email address.
- Replace `public/favicon.svg` with your own square SVG/PNG favicon if you want your own picture in the browser tab. If using PNG, update the icon link in `index.html` accordingly.
- Update project descriptions, skills and links to match your real work.
- Change colors and layout in `style.css`; interactions are in `script.js`.

No framework, paid service, or build dependencies are required.
