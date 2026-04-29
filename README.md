# AK Garage Door Pro

Single-page landing site for **AK Garage Door Pro** — same-day garage door
repair and installation, service in Boston and surrounding areas.

## Stack

- Static HTML/CSS — no framework, no build step
- Vanilla JS for mobile menu and form validation
- LocalBusiness + FAQPage JSON-LD schema for SEO
- Mobile-first, dark/futuristic theme (deep navy + electric cyan)

## Project structure

```
.
├── index.html              # Single-page site
├── assets/
│   ├── styles.css          # Dark theme, mobile-first
│   ├── logo.svg            # Primary logo
│   ├── logo-white.svg      # Logo for dark backgrounds (used in header/footer)
│   └── logo-mark.svg       # Icon-only mark (favicon)
└── images/                 # Real client portfolio photos
```

## Local preview

Just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Drop the folder on Netlify, Vercel, or Cloudflare Pages — no build needed.
For a custom domain, point the apex (`akgaragedoorsservices.com`) at the static host.

## Contact

- 📞 (857) 468-1852
- ✉️ Akgaragedoorpro@gmail.com
- 🌐 Service in Boston and surrounding areas
