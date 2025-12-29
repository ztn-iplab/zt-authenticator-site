# ZT-Authenticator Site

Official marketing site for **ZT-Authenticator** — a lightweight, device-bound
authenticator built for resilient MFA, offline-ready TOTP, and secure device approval.

## What this site covers

- Product positioning and key benefits
- Security story and device-bound approval flow
- RP-aware enrollment and multi-tenant adoption
- Deployment options (self-hosted, managed, enterprise)
- FAQ and contact CTA

## Key features highlighted

- Device-bound approvals to mitigate replay attacks
- Offline-ready TOTP generation
- RP-aware enrollment for domain-level policy alignment
- Multi-tenant support and fast onboarding
- Secure account transfer and telemetry hooks

## Tech stack

- Static HTML/CSS/JS
- No build step required

## Local preview

Open the page directly in a browser:

```bash
open /Users/patrick-m/Documents/zt-authenticator-site/index.html
```

Optional local server (if you want clean URLs):

```bash
python3 -m http.server 5173
```

Then visit `http://localhost:5173`.

## Structure

- `index.html` — content and layout
- `styles.css` — ZT-IAM palette and layout system
- `app.js` — reveal animations and contact form stub

## Branding & palette

The visual system mirrors the ZT-IAM palette:

- Primary: `#2962FF`
- Secondary: `#2E7D32`
- Backgrounds: `#1C1C3A`, `#212141`
- Surfaces: `#2D2F4A`

Fonts:

- Headings: **Unbounded**
- Body: **Space Grotesk**

## Deployment

This repo is ready for GitHub Pages or any static host:

- GitHub Pages: set the source to `main / root`
- Any CDN: upload `index.html`, `styles.css`, and `app.js`

## Contributing

PRs are welcome. Please keep:

- Consistent typography and spacing scale
- ZT-IAM palette alignment
- Security messaging accurate and conservative

## License

MIT — see `LICENSE`.
