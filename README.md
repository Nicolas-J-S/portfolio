# Portfolio — Nicolas Jason Smith

This repository contains a small static portfolio scaffold prepared for GitHub Pages.

Live domain configured: `nicolasjasonsmith.com`

What I pushed:

- `index.html` — Home / hero / projects list / contact
- `projects/sample-project.html` — Sample project detail page
- `images/favicon.svg` — Simple favicon
- `CNAME` — contains `nicolasjasonsmith.com` (tells GitHub Pages to use your custom domain)

DNS required (apex domain, set these A records at your registrar):

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

If you prefer `www.nicolasjasonsmith.com` as primary, instead point `www` CNAME to `Nicolas-J-S.github.io` and add a redirect from apex to `www` at your registrar.

How to enable GitHub Pages (one-time):

1. Go to this repository on GitHub: https://github.com/Nicolas-J-S/portfolio
2. Settings → Pages
3. Under "Build and deployment", choose `main` branch and `/ (root)` (or `/docs` if you move files there) as the publish source and save.
4. After DNS records propagate, GitHub will provision HTTPS automatically. It may take a few minutes to a few hours.

Editing content:

- Update `index.html` and files in `projects/` directly in the repo to change content.
- For images, add files to `images/` and update `src` references.

Need help connecting DNS or making design edits? Tell me what to change and I’ll update the repo.
