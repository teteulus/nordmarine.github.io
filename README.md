# Nord Marine – Static Site (GitHub Pages)

This folder contains a ready-to-publish static website (EN + RO).

## Structure
- index.html (English)
- ro/index.html (Romanian)
- assets/css/styles.css (styles)

## Publish on GitHub Pages (no code needed)
1) Create a GitHub account
2) Create a NEW repository named:
 nordmarine.github.io
3) Upload ALL files from this folder to the repository (root)
4) Go to Settings → Pages:
 - Source: Deploy from a branch
 - Branch: main / (root)
5) Your site will be live at:
 https://nordmarine.github.io

## Custom domain (www.nordmarine.ro) – free
In the repo:
1) Settings → Pages → Custom domain:
 set: www.nordmarine.ro
2) In your domain DNS, add:
 CNAME record:
 Name: www
 Value: nordmarine.github.io

Optional apex (nordmarine.ro without www):
- Set A records to GitHub Pages IPs (check GitHub docs for the current IPs),
 or use your registrar's forwarding from apex to www.

After DNS propagates:
- Back in GitHub Pages, enable "Enforce HTTPS".

## Edit content
Open index.html and ro/index.html and adjust:
- company statements
- phone/WhatsApp duty
- certifications/partners placeholders


## Added in v2
- /services/ (overview)
- /services/<service>.html (detail pages)
- /ro/servicii/ ... (Romanian equivalents)
