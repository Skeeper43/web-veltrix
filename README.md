# VELTRIX® — Beyond the Ordinary

A responsive creative-studio showcase built with Vite, vanilla JavaScript, and CSS. No backend required.

## Included
- Responsive black-and-red creative studio design
- Animated intro loader, orbit artwork, ticker, and scroll reveal
- Interactive project detail modals
- Mobile navigation
- Reduced-motion support and basic accessibility attributes
- Vite production build ready for Vercel

## Requirements
- Node.js 20.19+ or 22.12+ recommended for current Vite 6 tooling
- Git (optional, for GitHub deployment)

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Vite. In Termux, it is typically `http://127.0.0.1:5173`.

## Production build
```bash
npm run build
npm run preview
```
The production site is generated in `dist/`.

## Deploy to GitHub
Create an empty GitHub repository named `veltrix-showcase`, then from this folder run:

```bash
git init
git add .
git commit -m "Build VELTRIX creative studio showcase"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/veltrix-showcase.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username. If Git asks for a username/password, use GitHub's supported authentication flow or a personal access token; your normal account password is not accepted for Git operations over HTTPS.

## Deploy to Vercel
1. Sign in at https://vercel.com and choose **Add New → Project**.
2. Import your `veltrix-showcase` GitHub repository.
3. Framework preset: **Vite**.
4. Build command: `npm run build`.
5. Output directory: `dist`.
6. Click **Deploy**.

Vercel normally detects the Vite settings automatically.

## Customize
- Change studio copy, section text, and project labels in `index.html`.
- Change project modal descriptions in `src/main.js`.
- Change colors and visual styles in `src/style.css` under `:root`.
- Change the contact email `hello@veltrix.studio` in `index.html` to your real project email before publishing.

## Notes
The three projects shown are concept projects for the showcase design, not claims of real client work. The display artwork is generated with CSS, so no image assets are required. Google Fonts are loaded from Google Fonts; the layout falls back to system fonts if the connection is unavailable.
