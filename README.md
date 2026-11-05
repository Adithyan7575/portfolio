# Adithyan V portfolio

Static site, no build step. Cursor agents build the page as you scroll (CursorSwarm, MIT).

## Run
    python3 -m http.server 8787     # or: npm start
Open http://localhost:8787. In Antigravity you can also use any Live Server extension.

## Edit
- Content: `index.html`
- Look: `style.css` (colors are variables at the top, `--hot` is the orange)
- Agents: the `new CursorSwarm({...})` call at the bottom of `index.html`
- TODO: replace `YOUR-LINKEDIN-ID` in the contact section with your LinkedIn handle

## Deploy
Upload the folder to Netlify, Vercel, Cloudflare Pages or GitHub Pages.
