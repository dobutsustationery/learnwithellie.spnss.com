# Learn with Ellie Press

Public book website for **https://learnwithellie.spnss.com**.

Plain HTML and CSS, published by GitHub Pages from the root of `main`. No build step or third-party scripts are required. `CNAME` declares the custom domain. `/next` redirects to `/next/`, where the upcoming-books page lives.

- `index.html`: publisher introduction and Volume 1 information
- `next/index.html`: upcoming books; update when titles and dates are confirmed
- `assets/site.css`: responsive site styling
- `assets/`: publisher mark and selected cat illustrations

Cloudflare holds a DNS-only CNAME from `learnwithellie.spnss.com` to `dobutsustationery.github.io`. Credentials remain in the private authoring workspace; this repository contains no deployment secrets. Never commit `.env` files.

Book text and artwork © Learn with Ellie Press. All rights reserved.
