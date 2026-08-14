# CTR Title, LLC — Website

Modern rebuild of [ctrtitle.com](https://www.ctrtitle.com/) with an Apple-inspired
aesthetic: glassmorphism navigation, floating dynamic cards, soft depth, gradient
mesh backgrounds, and scroll-reveal animations. Brand colors, logo, imagery, and
copy are carried over from the original site.

## Stack

Static, dependency-free HTML / CSS / JavaScript. No build step, no frameworks —
just open the files or serve the folder.

## Pages

| File | Page |
|------|------|
| `index.html` | Home |
| `services.html` | Services (Residential & Land, Commercial, Closing) |
| `home-owners.html` | Home Owners |
| `contact.html` | Contact & Order Title |

## Structure

```
.
├── index.html
├── services.html
├── home-owners.html
├── contact.html
└── assets/
    ├── css/styles.css   # design system + all page styles
    └── js/main.js       # nav, scroll reveal, card tilt, accordion, form
```

## Run locally

```bash
# any static server works, e.g.
python3 -m http.server 8000
# then open http://localhost:8000
```

## Notes

- **Brand palette** (navy + blue), tokens live at the top of `assets/css/styles.css`.
- **Images / logo** are currently referenced from the original Wix CDN so the site
  matches the existing brand instantly. To self-host, drop the files in
  `assets/img/` and update the `src` paths.
- The contact form uses a `mailto:` handoff to `orders@ctrtitle.com` (no backend).
  Swap in a form service (Formspree, Basin, GHL, etc.) when ready.
- Company details: **704-467-3031** · **orders@ctrtitle.com** · PO Box 851,
  Oakboro, NC 28129 · serving all NC & SC counties.

© CTR Title, LLC.
