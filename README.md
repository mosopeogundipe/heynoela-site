# heynoela.com

The website for Noela: a coming-soon page, privacy policy and support page.

Plain static HTML and CSS, served by GitHub Pages. Pushing to `main` publishes it to https://heynoela.com within a minute or two.

Preview locally with `python3 -m http.server 8765`, then open http://localhost:8765.

Don't delete `CNAME` (custom domain), `.nojekyll` (lets GitHub serve `.well-known`) or `.well-known/microsoft-identity-association.json` (Microsoft publisher-domain verification).
