Fisdel Green Consult Ltd - Static Website (deploy-ready)

Files included:
- index.html
- pages/about.html
- pages/services.html
- pages/sectors.html
- pages/projects.html
- pages/why.html
- pages/contact.html
- assets/styles.css
- assets/script.js
- assets/img/ (real logo, icon, favicon)

How to use locally:
1. Download and extract the ZIP package.
2. Open index.html in a browser, or run a local static server
   (e.g. `python3 -m http.server` or `npx serve`) from this folder.
3. Navigate across pages using the top menu.

Deployment:
- Pure static HTML/CSS/JS, no build step and no backend required.
- Deploys as-is to Netlify, Vercel, Cloudflare Pages, GitHub Pages, or
  any static host. See DEPLOY_CONTEXT.md (one level up) for the full
  handoff brief.

Known gaps / decisions still open:
- The contact form (pages/contact.html) is visual only -- it is not
  wired to any backend or form service. Pick a form handler as part of
  deployment (Formspree, Netlify Forms, a small serverless function, etc.).
- All contact details (website .com / .com.ng, both emails, phone) are
  wired throughout the site and verified working.
- Real Fisdel Green logo and icon are in place across every page.
