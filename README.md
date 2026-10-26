# Neon Rush — One More Try

A lightweight single-file arcade game built with HTML, CSS, Canvas 2D, and vanilla JavaScript.

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Use the left/right arrow keys or A/D, or tap the left/right half of the playfield.
4. Tap **Play Now** to begin.

## Deploy with GitHub + Vercel
1. Create a GitHub repository named `neon-rush`.
2. Upload `index.html` and `README.md` to the repository root.
3. Sign in to Vercel and choose **Add New → Project**.
4. Import the `neon-rush` repository.
5. For a plain static HTML site, no framework or build command is needed. If Vercel asks for an output directory, leave it empty/default unless its current interface specifies otherwise.
6. Click **Deploy**. Open the generated URL and test on both desktop and mobile.
7. To update the game, edit `index.html` on GitHub and commit; Vercel will redeploy automatically when the repository is connected.

## Monetag: recommended approach
- First deploy and test the game without ads.
- Check with Monetag whether your exact `vercel.app` URL can be approved and monetized. Some advertising networks restrict free hosted subdomains; do not assume approval.
- For a game, prefer a Monetag-approved display/banner placement outside the active playfield if that format is available and supported for your account/site.
- A Direct Link/SmartLink is a clickable destination, not a display ad. If you use one, make it a clearly labelled, separate “Sponsored offer” link away from all game controls. Do not trigger it on taps/swipes used to play, and do not incentivize or generate accidental clicks.
- Avoid OnClick/Popunder formats for the first release because they can interrupt play and may create a poor user experience. Use them only if Monetag confirms they are allowed for your site and you can implement them in line with its rules and applicable consent requirements.
- Paste only the exact code or URL from your Monetag publisher dashboard. Never use invented zone IDs or copied code from another publisher.
- Do not click your own ads or buy fake traffic. Follow Monetag's current publisher policies.

## Notes
- The game stores the personal-best score locally in the browser using `localStorage`.
- No accounts, backend, or external game assets are required.
- Advertising is intentionally not enabled in this starter build.
