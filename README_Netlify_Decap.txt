Quick deploy (no code changes needed):

FILES
- index.html
- /admin/index.html
- /admin/config.yml
- /data/items.json
- /images/uploads/.gitkeep

STEPS
1) Create a new GitHub repo and upload all files keeping the same folders.
2) Netlify → New site from Git → select your repo → Deploy.
   - Build command: (leave empty)  •  Publish directory: /
3) Netlify → Identity: Enable → Invite yourself → Enable Git Gateway.
4) Visit /admin on your site → Log in → Edit/Publish products.
5) Upload images in the CMS; they go into /images/uploads automatically.
6) Your homepage reads from /data/items.json (no backend).

Tip: rename the site in Netlify and add a custom domain later if you want.
