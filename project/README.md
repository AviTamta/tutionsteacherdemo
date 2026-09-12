# Tuitionsteacher — Static Site

Plain HTML/CSS site, ready to deploy as-is (no build step needed).

## Structure
```
/
├── index.html         ← homepage
├── coming-soon.html   ← placeholder page (linked from every button/nav item)
└── images/            ← all photos, logo, and category images
```

## Deploy on Vercel (via GitHub)
1. Push this whole folder to a new GitHub repo (keep the `images/` folder alongside the HTML files — don't rename or move it).
2. Go to vercel.com → **Add New Project** → import that GitHub repo.
3. Framework preset: choose **Other** (or leave as detected "Static").
4. Leave Build Command and Output Directory empty — Vercel will serve the files as-is.
5. Deploy. Your site will be live at the generated `*.vercel.app` URL.

## Notes
- All buttons, nav links, and CTAs currently point to `coming-soon.html` since the rest of the site isn't built yet.
- WhatsApp float button links to `wa.me/918860616302`.
- Update social links in the footer (`Facebook`/`Twitter`/`Instagram`/`Youtube`) once you have the real URLs — currently they point to `coming-soon.html`.
