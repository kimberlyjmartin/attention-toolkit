# Attention Toolkit — GitHub Pages setup

This is a static site: 6 HTML files + 1 stylesheet, no build step needed.

## Fastest path (no command line)

1. Create a new repository on GitHub — name it something like `attention-toolkit`.
2. On the repo's main page, click **Add file → Upload files**.
3. Drag in all 6 files: `index.html`, `cognitive-load.html`, `relevance.html`, `modality.html`, `belonging.html`, `autonomy.html`, and `style.css`.
4. Commit the upload.
5. Go to **Settings → Pages** (left sidebar).
6. Under "Build and deployment," set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
7. GitHub gives you a live URL after a minute or two, usually:
   `https://YOUR-USERNAME.github.io/attention-toolkit/`

That's it — no Git commands required for this method.

## If you'd rather use git locally

```
git clone https://github.com/YOUR-USERNAME/attention-toolkit.git
cd attention-toolkit
# copy the 7 files in here
git add .
git commit -m "Add toolkit site"
git push
```

Then turn on Pages the same way (step 5–6 above).

## Updating later

Any time you want to add a strategy, edit the relevant HTML file (each strategy is one `<div class="card">` block — copy/paste one and change the text) and re-upload, or `git push` again if using the command line. Changes usually go live within a minute.
