# Nomi Studio — Website

A five-page, fully animated static website. Plain HTML, CSS and JavaScript — no build step, no frameworks.

## Pages
- `index.html` — Home
- `services.html` — Services (auto-rotating capabilities, packages, FAQ)
- `work.html` — Work (filterable project grid)
- `studio.html` — The Studio (principles + founder)
- `contact.html` — Contact (interactive project brief)

## Run it locally
Open `index.html` in a browser, or run a tiny server from this folder:

    python -m http.server 8000

then visit http://localhost:8000

## Go live (free)
Drag this whole folder into **Netlify Drop** (app.netlify.com/drop), or push it to GitHub and turn on **GitHub Pages** / import it into **Vercel**. Then connect your domain.

## (Optional) Also receive briefs by email
1. Create a free form at formspree.io and copy its endpoint URL.
2. In `contact.html`, find `data-endpoint=""` on the `<form id="brief">` and paste the URL inside the quotes.
Briefs (name, email, company, details, chosen services and budget) will then arrive in your inbox.

## Fill in before launch
- `[hello@nomistudio.com]` and `[@nomistudio]` — your real email and Instagram (all pages)
- Instagram / LinkedIn links in the footer (currently point to the homepages)
- `[₹ —]` package prices — services.html
- `[Project name]` / `[Project image]` — index.html featured work and work.html
- Budget ranges on contact.html, if you want different ones

## WhatsApp
Connected to +91 75749 75787 — the floating chat button (every page), the mobile menu, the footer and the Contact form all open WhatsApp. The Contact form sends the full brief (name, email, brand, services, budget, details) pre-written into the chat. To change the number, search the files for `917574975787`.

## Notes
- Scroll-linked effects (progress bar, scroll reveals, image wipes) use modern CSS scroll timelines — full effect in Chrome/Edge; other browsers simply show the content.
- All motion respects the visitor's "reduce motion" setting.
