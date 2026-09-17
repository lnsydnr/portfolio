# Lane Sidner — Portfolio

Personal portfolio site for Lane Sidner, SOC Analyst / Cybersecurity & IT professional.

**Live site:** _add your custom domain or `*.pages.dev` URL here once deployed_

## Stack
- Static HTML / CSS, no build step
- Fonts: IBM Plex Sans + IBM Plex Mono (Google Fonts)
- Hosted on [Cloudflare Pages](https://pages.cloudflare.com/), deployed automatically on push to `main`

## Structure
```
.
├── index.html          # Page markup
├── css/
│   └── style.css        # All styling
├── _headers             # Cloudflare Pages custom HTTP headers (security headers)
└── README.md
```

## Local preview
No build tools required — just open `index.html` in a browser, or serve it locally:
```
python3 -m http.server 8080
```

## Deployment
Connected to Cloudflare Pages via GitHub integration. Build command: none. Output directory: `/`.
Every push to `main` triggers a new deploy.
