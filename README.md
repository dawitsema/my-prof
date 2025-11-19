## Dawit Sema Portfolio

Single-page backend automation portfolio built with vanilla HTML/CSS/JS. Includes responsive layout, mobile nav, animated sections, custom pointer trail, and contact form posting to Google Apps Script.

### Local Development
```bash
npm install -g serve   # or any static server
serve .
```
Open the printed localhost URL to preview the site (required for fetch-based contact form to work).

### Deployment (Netlify via GitHub)
1. Push this folder to a GitHub repository (root should contain `index.html`).
2. On Netlify:
   - New Site → Import from Git → pick repo & branch.
   - Build command: `npm run build` (leave blank) since this is static.
   - Publish directory: `.` (root).
3. After deploy, update the Live Site Settings → General → Site details for a custom domain/subdomain.

### Environment Notes
- Contact form posts to the Apps Script endpoint configured in `index.html`. Keep that deployment live and CORS-enabled.
- Favicon/logo references `my-logo.png` in the project root.


# my-prof
