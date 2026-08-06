# Sales Job Landing Page

A single-page, no-build landing page for recruiting sales reps — built for
Facebook/Meta, LinkedIn, and Google ad traffic. Dark, high-energy theme with
lime/orange gradient accents. No external dependencies (fonts, JS libraries,
build tools), so it loads fast, which matters for ad quality scores.

Files:
- `index.html` — all page content
- `styles.css` — theme, layout, responsive rules
- `script.js` — scroll-reveal animation only

## Before you publish this as a live ad, edit these placeholders

1. **Company name** — set to "True Imperium." Find/replace it across
   `index.html` if that changes.
2. **Apply button link** — in `index.html`, the `#apply` section points to
   `mailto:trueimperiumcareers@gmail.com`. Make sure that Gmail inbox exists
   and is monitored. Once a `careers@trueimperium.com` domain email is set
   up (see Google Workspace or free forwarding from your domain registrar),
   swap the `href` to that, or to a real ATS/job board link (Indeed,
   LinkedIn Jobs, Greenhouse, Workable, a Google/Typeform form, etc.).
3. **Compensation details** — search `EDIT ME` in the "How You're Paid"
   section and replace the placeholder note with your actual base pay,
   commission structure, and pay cycle. Avoid vague/unverifiable income
   numbers in ad copy — most ad platforms and consumer-protection rules
   require job compensation claims to be accurate.
4. **Location & contact info** — footer has `[Your City], [State]` and a
   placeholder phone/email. Replace with real details.
5. **Social share image** — the `og:image` meta tag in `index.html` is a
   placeholder. Add a real 1200×630 image and host it somewhere public
   (e.g. same host as this page) so Facebook/LinkedIn show a proper preview
   card when the link is shared.
6. **Logo** — there's no image logo; the header uses a text wordmark. Swap
   in an `<img>` in the `.wordmark` if you have a logo file.

## Deploying

This is static HTML/CSS/JS — any static host works:
- **GitHub Pages**: enable Pages on this repo, serve from the root.
- **Netlify / Vercel**: drag-and-drop the folder or connect the repo.
- Any web server: just copy the three files.

## Local preview

Open `index.html` directly in a browser, or run a simple local server:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
