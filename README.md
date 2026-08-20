# TikTok Clipper — Legal & Platform Pages

These 3 HTML pages are required for TikTok Developer Portal app review.

## Files

| File | URL to put in TikTok Portal |
|------|-----|
| `index.html` | **Platform URL** — Landing page describing the app |
| `terms.html` | **Terms of Service URL** |
| `privacy.html` | **Privacy Policy URL** |

---

## Deploy on GitHub Pages (free)

1. Create a **public** GitHub repo called `tiktok-clipper-pages`

2. Copy these 3 files into the repo root

3. Push to GitHub:
```bash
git init
git add .
git commit -m "Add TikTok Clipper legal pages"
git remote add origin https://github.com/YOUR_USERNAME/tiktok-clipper-pages.git
git push -u origin main
```

4. Go to **Settings → Pages → Source: Deploy from branch → main**

5. Your URLs will be:
```
https://YOUR_USERNAME.github.io/tiktok-clipper-pages/
https://YOUR_USERNAME.github.io/tiktok-clipper-pages/terms.html
https://YOUR_USERNAME.github.io/tiktok-clipper-pages/privacy.html
```

6. Put these 3 URLs in the TikTok Developer Portal when submitting for review.

---

## Fill in the TikTok Portal

| Field | Value |
|-------|-------|
| **Platform URL** | `https://YOUR_USERNAME.github.io/tiktok-clipper-pages/` |
| **Terms of Service URL** | `https://YOUR_USERNAME.github.io/tiktok-clipper-pages/terms.html` |
| **Privacy Policy URL** | `https://YOUR_USERNAME.github.io/tiktok-clipper-pages/privacy.html` |

Then click **Submit for Review**.
