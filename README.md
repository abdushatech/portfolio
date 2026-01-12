Deploy in 2 minutes
-------------------
1. Push this folder to a NEW GitHub repo.
2. GitHub → Settings → Pages → Source: Deploy from branch → Save.
3. Visit `https://yourname.github.io/repo-name/` — live!

Or drop the folder into Netlify drag-and-drop — instant HTTPS.

Update content without touching HTML
-----------------------------------
- Edit `data.json` → refresh browser.
- Daily posts: use the “Add new post” form (owner only) or manually edit `posts.json` and commit.

Replace photo & PDF
-------------------
- Add `assets/img/abdilselam.jpg` (or change path in data.json).
- Replace `assets/resume.pdf` (linked by “Download Résumé”).

Contact form
------------
- Grab free endpoint: https://formspree.io → paste ID in script.js.
- Or switch to Netlify Forms by adding `netlify` attribute to form.

SEO
---
- Edit meta tags in index.html `&lt;head&gt;`.
- Add `sitemap.xml` & `robots.txt` if desired (generator tools online).

Performance
-----------
- Images auto-scale (CSS).  
- No external JS frameworks → 100 Lighthouse score out-of-the-box.
