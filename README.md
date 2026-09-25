# Privilio — Marketing Site

Static marketing + legal site for **Privilio**, a local-first private contact manager
(contacts stay on your device, with a PIN-protected vault). No servers, no accounts.

## Pages
| File | URL on Netlify |
|------|----------------|
| `index.html`   | `/` — landing page |
| `privacy.html` | `/privacy` |
| `terms.html`   | `/terms` |
| `contact.html` | `/contact` — support emails |
| `about.html`   | `/about` — stub (coming soon) |
| `blog.html`    | `/blog` — stub (coming soon) |
| `preview.html` | `/preview` — interactive app preview (disallowed in robots.txt) |
| `email.html`   | launch email template (not linked in nav) |
| `robots.txt`   | `/robots.txt` |
| `sitemap.xml`  | `/sitemap.xml` |

## Deploy on Netlify
**Option 1 — connect this repo (continuous deploy):**
1. Netlify → *Add new site* → *Import from Git* → pick this repo.
2. Build command: *(none)* · Publish directory: `.`
3. Deploy. Every push to `main` redeploys automatically.

**Option 2 — drag & drop:** download the repo as a ZIP and drop it at
<https://app.netlify.com/drop>.

Clean URLs (`/privacy`, `/terms`, `/preview`) work automatically on Netlify.

Built by Adapting Services Limited · Canada.
