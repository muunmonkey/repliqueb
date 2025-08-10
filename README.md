# CMS-ready Instagram-style Grid

This is your cleaned, CMS-ready build of the handbag grid, adapted for **Decap (Netlify) CMS**.

## What's included
- `index.html` — your original file, cleaned of demo content and wired to load data from `data/products.json`.
- `admin/` — Decap CMS dashboard (go to `/admin` once deployed on Netlify).
- `data/products.json` — starts empty; CMS writes here.
- `logo.svg` — placeholder logo; replace with your own or point the `<img src="logo.svg">` elsewhere.
- `static/uploads/` — will be auto-created by the CMS when you upload media.

## Deploy on Netlify (quick)
1. Push this folder as a Git repo (GitHub/GitLab/Bitbucket).
2. Create a new site on Netlify from that repo.
3. Enable **Identity** and **Git Gateway** in Netlify (if you keep the default `git-gateway` backend).
4. Invite yourself as a user, log in at `/admin`, and start adding products.
5. Your data will be written into `data/products.json` and the grid will update automatically on refresh.

If you prefer GitHub backend instead of Git Gateway, change `backend:` in `admin/config.yml` accordingly.
