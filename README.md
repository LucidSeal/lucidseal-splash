# LucidSeal Splash Page

This repository contains the static site for **LucidSeal**. It includes the landing splash page, badge assets, and basic trust-related meta files.

## Contents

- `index.html` — main splash page
- `404.html` — custom error page
- `badge-dark.svg` — primary LucidSeal badge (navy stroke on light background)
- `badge-light.svg` — inverse badge (white stroke on dark background)
- `badge-favicon.svg` — minimalist badge for favicon/UI
- `lucidseal-badge-set.svg` — SVG symbol set with dark/light variants
- `robots.txt` — search engine crawling rules
- `security.txt` — security contact and disclosure information
- `LucidSeal_Badge_Guidelines.md` — badge usage guidelines

## Deployment

### Cloudflare Pages
1. Push this repository to GitHub.
2. In Cloudflare Dashboard → **Pages**, create a new project linked to the repo.
3. Set build command to **None** (static site).
4. Set output directory to root (`/`).

### Vercel (alternative)
1. Import the repo in Vercel dashboard.
2. No build command required.
3. Output directory: root (`/`).

## Development

No frameworks or dependencies required. Pages are plain HTML/CSS with inline assets.

To run locally:
```bash
python3 -m http.server 8080
```
Then visit [http://localhost:8080](http://localhost:8080).

## License

© LucidSeal. Content is provided as-is. The badge and wordmark are reserved for use within the LucidSeal project and its participants.
