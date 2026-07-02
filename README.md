# Apoorva D M — AgriTech Meta Ads Case Study

Next.js portfolio case study site (App Router).

## Run locally
```
npm install
npm run dev
```
Open http://localhost:3000

## Deploy to Vercel
```
npm i -g vercel
vercel
```
Or push this folder to a GitHub repo and import it at vercel.com/new — no config needed, Vercel auto-detects Next.js.

## Notes
- Resume PDF lives at `public/resume.pdf` — the "Resume" link on the Contact section points to `/resume.pdf`. Replace that file to update your resume.
- All copy/content is in `app/page.js`. Styles are in `app/globals.css`.
- Charts are hand-built inline SVG (no external chart library), rendered client-side in `app/page.js` via a `useEffect`.
