# A‑Tech — Green Gas Consumer Billing (PWA)

## Quick Start (Local)
1. Install Node.js LTS.
2. In project folder, run:
   ```bash
   npm install
   npm run dev
   ```
3. Open http://localhost:3000

## Build
```bash
npm run build
```
Output will be in `dist/`.

## Vercel Deploy (No CLI)
1. Go to https://vercel.com → New Project → Import → drag‑drop your folder.
2. Framework: **Vite** (auto-detected) → Build Command: `vite build` → Output Dir: `dist`.
3. Deploy. Your live URL is ready.

## PWA Install
- After first load, browser will show “Install App / Add to Home Screen”.
- Works offline via Service Worker + IndexedDB.

## Notes
- Overdue & interest auto‑calc is **not included** (as requested).
- Partial payments are supported via “Mark Paid / Partial”.
