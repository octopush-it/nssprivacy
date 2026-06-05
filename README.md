# Network Superstar Static Site

This folder is the Cloudflare Pages output for the Network Superstar app page and privacy policy.

Suggested Cloudflare Pages settings:

- Build command: leave blank
- Build output directory: `site`
- Privacy policy URL path: `/privacy`

Files:

- `index.html`: app landing/support page
- `privacy.html`: Apple-ready privacy policy
- `_redirects`: maps `/privacy` to `privacy.html`
- `_headers`: basic security and cache headers
