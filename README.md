Ezwipe privacy site (static)

This small repo contains a single static privacy page served via GitHub Pages.

How to publish

1. Create a new public GitHub repository (example name: `ezwipe-website`).
2. From this machine, add the remote and push:

```bash
cd /Users/nicolasluk/PycharmProjects/ezwipe-website
git init
git add .
git commit -m "Add privacy policy"
# replace <your-github> and repo name
git remote add origin git@github.com:<your-github>/ezwipe-website.git
git branch -M main
git push -u origin main
```

3. On GitHub: Settings → Pages → Source → select `main` branch and `/docs` folder (or root if you moved files) → Save.
4. GitHub will publish at:
   `https://<your-github>.github.io/ezwipe-website/docs/privacy.html` (or similar). Use the provided URL in Play Console / App Store Connect.

Notes

- You can rename the repo (e.g., `privacy.ezwipe`) — the GitHub Pages URL will change accordingly.
- If you want a custom domain (e.g., `https://ezwipe.app/privacy`) you can configure it in GitHub Pages and point DNS to GitHub as documented by GitHub.

What I created locally

- `docs/privacy.html` — store-ready privacy page.
- `README.md` — instructions to push & enable Pages.

Next steps I can do for you

- Prepare commit and instructions customized with your GitHub username and push the files.
- Or, if you prefer, I can instead add `docs/privacy.html` to this repo and prepare Netlify/Vercel steps to publish from the private repository.
