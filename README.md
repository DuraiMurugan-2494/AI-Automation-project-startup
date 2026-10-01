# AI Automation Studio — Website Package

## Included
- `index.html` — main responsive business website
- `thank-you.html` — post-enquiry page
- `404.html` — custom not-found page
- `privacy.html` — privacy-policy template
- `terms.html` — terms template
- `robots.txt` — search crawler instructions
- `sitemap.xml` — SEO sitemap template
- `favicon.svg` — site icon
- `_headers` — basic security headers
- `README.md` — deployment checklist

## Before launch
1. Choose the legal/business name.
2. Buy a domain.
3. Replace `AI Automation Studio` with the final brand name.
4. Replace `hello@yourcompany.com` everywhere.
5. Replace `YOUR-DOMAIN.com` in `robots.txt` and `sitemap.xml`.
6. Review privacy and terms with your legal/tax adviser.
7. Add a real company address/contact details if required.
8. Add analytics only after deciding on your cookie/privacy approach.

## Recommended hosting
For this static site, Netlify is the easiest first production host because it supports static deployment, custom domains/SSL, and form handling. Cloudflare Pages is an excellent alternative for Git-based deployment and global delivery.

### Netlify quick deployment
1. Create a Netlify account.
2. Add a new site.
3. Drag the contents of this folder into the Netlify deploy area, or connect the folder through a Git repository.
4. In Domain management, add your custom domain.
5. Confirm the Netlify form `automation-enquiry` appears under Forms after the first deployment.
6. Configure email notifications for form submissions.
7. Test the contact form from a private/incognito browser window.

### Cloudflare Pages
1. Put the package in a GitHub repository.
2. Create a Cloudflare Pages project connected to that repository.
3. Use the repository root as the build output for this static site; no framework build is required.
4. Add your custom domain under Custom domains.
5. For the contact form, add a form backend/service or Cloudflare Worker/Pages Function because this package's form is optimized for Netlify's form handling.

## Suggested production architecture
Domain registrar → DNS/CDN → Static hosting → Website → Lead form → Business email → Analytics/Search Console

Keep API keys and credentials out of this static website. If the business later adds AI demos, CRM integration, authentication or database functionality, move those functions behind a server-side API.


## UI QA fixes applied in this revision
- Fixed the mobile navigation menu appearing as an unwanted block on desktop.
- Prevented the rotated hero preview card from creating small-screen clipping.
- Added keyboard-visible focus states for interactive controls.
- Improved mobile menu link spacing and separators.
- Added Privacy and Terms links to the footer.
- Improved footer wrapping on narrow screens.
- Added horizontal overflow protection for mobile layouts.
