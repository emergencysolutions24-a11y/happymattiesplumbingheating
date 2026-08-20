# Happy Matties Plumbing And Heating — Site

No npm, no build step. Double-click `index.html` to preview locally.

## What changed in this update
- Restored the detailed **Services** section (id `#services`) with the full
  two-column checklist from the old site.
- Restored the detailed **Heating Services** section (id `#heating-services`)
  with its own checklist.
- Added a "Heating Services" link to the main nav.
- The old simpler services block (the "Why choose us" list + testimonial)
  is kept further down the page as `#why-choose` — nothing was deleted.
- Phone/email throughout stayed as-is: 07520654824 / johnlondon1449@gmail.com.

## Still missing — add these before going live
- `images/logo.png` and `images/gassafe.png` — not included, the page will
  show broken image icons until you drop real files into `images/`.
- `images/001.jpg`, `008.jpg`, `014.jpg`, `004.jpg`, `003.jpg` — hero slider
  and feature photos, same deal.
- A `#gallery` section — the nav links to `#gallery` but there's no gallery
  section on the page yet. Add one, or point the nav link elsewhere.
- The JSON-LD block in `<head>` still says `"name": "Plumbing and Heating"`
  instead of the real business name — worth fixing for SEO.

## Hosting
Drag the whole folder onto app.netlify.com/drop for a free live link, then
connect a custom domain in Site Settings → Domains.
