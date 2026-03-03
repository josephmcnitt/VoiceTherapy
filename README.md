# Voice Therapy — Website

Static website for a trans-owned, trans-run voice therapy practice. Built for clarity, trust, and community (mutual aid, featured artists, events).

## What’s included

- **Pages:** Home, About, Voice therapy, Current events, Contact
- **Design:** Calm, professional layout with placeholder areas for artwork (hero, side panels, featured artist). Replace placeholders when you have final artwork and style.
- **Footer:** Mutual-aid line on every page.
- **Contact:** Uses `emmcnitt14@gmail.com` until the business email from Mick is ready—then update the mailto link and any visible address in `contact.html` and the footer if needed.

## Run locally

Open the site from the project folder:

- **Option A:** Double-click `index.html` in a file manager to open in your browser.
- **Option B:** From a terminal in this folder, run a simple server (e.g. `npx serve .` or `python -m http.server 8000`) and go to `http://localhost:8000` (or the port shown).

No build step required; it’s plain HTML and CSS.

## Go live (deployment)

1. **Hosting:** Use any static host—e.g. [Netlify](https://netlify.com), [Vercel](https://vercel.com), or [GitHub Pages](https://pages.github.com). Drag this folder (or connect the repo) and deploy; no extra config needed.
2. **Domain:** When you have a business domain, add it in the host’s dashboard and point DNS to the host’s instructions.
3. **Business email:** When Mick sends the business email, replace `emmcnitt14@gmail.com` in:
   - `contact.html` (main link and “Email us” text)
   - Any other place you mention the address.
4. **Artwork and style:** Drop real images into the placeholder areas (hero, side art, featured artist on Current events). Update `css/style.css` if you get a style mockup (colors, fonts, spacing).

## File structure

```
SpeechBusiness/
├── index.html          # Home
├── about.html
├── voice-therapy.html
├── current-events.html
├── contact.html
├── css/
│   └── style.css       # Shared styles
├── notes               # Your rough notes
└── README.md           # This file
```

When you add real images, put them in an `images/` (or `img/`) folder and reference them in the HTML where the placeholder divs are.
