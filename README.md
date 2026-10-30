# CABGRAPHICS Portfolio (Atingua Abayom)

A static website: no build step, no dependencies to install.

## Files
- `index.html`  the whole site (HTML, CSS, JavaScript)
- `assets/`     all images (hero photo, logo, brand logos, portfolio flyers)
- `vercel.json` hosting settings (clean URLs and image caching)
- `favicon.ico`, `favicon-32x32.png`, `apple-touch-icon.png`  browser-tab and home-screen icons (CAB logo)

## Deploy on Vercel
**Option A: drag and drop (fastest)**
1. Go to vercel.com and sign in.
2. Click Add New > Project, then use "Deploy" with this folder (or use the Vercel CLI: `npm i -g vercel`, then run `vercel` inside this folder).
3. Framework preset: **Other**. Build command: leave empty. Output directory: leave empty (the root).

**Option B: GitHub**
1. Create a GitHub repository and upload everything in this folder.
2. In Vercel choose Add New > Project, import the repository, and click Deploy.

## Good to know
- Tailwind CSS and the Google Fonts (Syne, Manrope, Montserrat) load from the internet, so the site needs a connection to display correctly.
- To change a portfolio project, edit the `W` list in the script near the bottom of `index.html`. Image files go in `assets/`.
- WhatsApp and email links are in the footer of `index.html`.
