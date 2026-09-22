# JosivexEcom — Mentorship Landing Page

A single-file static site (`index.html`). No build step, no dependencies.

## Deploy on Vercel

1. Push this repo to GitHub.
2. On https://vercel.com → **Add New Project** → import the GitHub repo.
3. Framework preset: **Other** (or "No Framework"). Leave Build Command and Output Directory blank — Vercel will serve `index.html` as a static site automatically.
4. Click **Deploy**.

Every push to your main branch will auto-redeploy.

## Editing later

Everything — HTML, CSS, JS, and the result screenshots — lives in the one `index.html` file (images are embedded as base64, so there's nothing else to host or link). Open it in any editor, or hand it back to Claude with the file attached.

## Notes

- The application form on the page is front-end only right now — it validates and shows a confirmation, but submissions aren't sent or stored anywhere. Wire it to a form backend (e.g. Formspree, a Google Sheet via Apps Script, or your own API route) if you need submissions to actually reach you.
- WhatsApp: wa.me/447462699360 · Telegram: t.me/Josivex — both are linked throughout the page.
