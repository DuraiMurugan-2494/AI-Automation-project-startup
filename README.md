# AI Automation Studio — Render-ready website

This is a plain static HTML/CSS/JavaScript website prepared for **Render Static Sites**.

## Render configuration

- Repository: `DuraiMurugan-2494/AI-Automation-project-startup`
- Branch: `main`
- Build command: `echo "No build required"`
- Publish directory: `.` (repository root)
- Auto deploy: enabled for commits to `main`

Render static sites are served through a global CDN, support automatic Git deployments, custom domains and managed TLS.

## Deployment

1. In Render, choose **New → Static Site**.
2. Connect GitHub and select `DuraiMurugan-2494/AI-Automation-project-startup`.
3. Select `main`.
4. Set Build Command to `echo "No build required"`.
5. Set Publish Directory to `.`.
6. Create the site.

The included `render.yaml` can also be used with a Render Blueprint.

## Contact form

The Netlify-specific form configuration has been removed. The website is now host-independent.

The current staging fallback opens an email draft using the placeholder `hello@yourcompany.com`. **Do not treat the form as production-ready yet.**

After the Render deployment is verified, we can connect the form to a separate backend without changing the hosting provider.

## Before launch

- Replace `AI Automation Studio` with the final brand name.
- Replace `hello@yourcompany.com`.
- Replace `YOUR-DOMAIN.com` in `robots.txt` and `sitemap.xml`.
- Review privacy and terms.
- Connect the production form backend.
- Add the final custom domain.
