# Nathan-Russ.github.io

Personal portfolio site — GitHub Pages user site.

## Deploy this (2 minutes)

GitHub Pages serves a **user site** automatically from a repo named exactly
`<your-username>.github.io`. Since your GitHub username is `Nathan-Russ`, this
repo needs to be named `Nathan-Russ.github.io` for the automatic setup to work.

1. Create a new **public** repo on GitHub named exactly `Nathan-Russ.github.io`
   (case doesn't matter, but the name must match your username + `.github.io`).
2. Push this folder's contents to that repo's `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/Nathan-Russ/Nathan-Russ.github.io.git
   git push -u origin main
   ```
3. Go to the repo's **Settings → Pages**. For a `<username>.github.io` repo,
   this is usually already enabled and serving from `main` / `root` — if not,
   set **Source** to "Deploy from a branch", branch `main`, folder `/ (root)`.
4. Your site will be live at **https://nathan-russ.github.io/** within a
   minute or two (GitHub shows the URL and a green checkmark on the Pages
   settings page once it's ready).

## Editing

It's a single self-contained `index.html` — all CSS and the one small
animation script are inline, no build step. Open it in any editor, change the
text, save, commit, and push; GitHub Pages redeploys automatically on every
push to `main`.

To preview changes locally before pushing, just open `index.html` directly in
a browser, or run a quick local server from this folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## What's next

The "More to come" section is there deliberately — as new projects or
publications happen, add a new `.project` block following the same pattern as
the existing two, and expand the "Research focus" section as your work
develops. The layout was built with that growth in mind rather than as a
fixed, finished page.
