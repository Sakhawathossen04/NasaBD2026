# NASA Eyes on the Earth — Fullscreen Embed//..

This repository does **not** copy NASA Eyes source code.

It embeds the official live NASA Eyes on the Earth application full-screen
using an iframe. NASA documents website embedding for Eyes experiences.

## Run locally

You can simply open `index.html`, or serve the folder:

```bash
python -m http.server 8000
```

Then open:

http://localhost:8000

## Push to GitHub

```bash
git init
git add .
git commit -m "Add fullscreen NASA Eyes embed"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

## GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select `main` and `/ (root)`.
5. Save.

GitHub will publish the wrapper as a live website.

## Vercel

Import the GitHub repository into Vercel as a static project.
No build command is required.

## Important

Your repository contains only the wrapper page. The NASA application,
its JavaScript, models, imagery and other internal assets continue to load
from `eyes.nasa.gov`.

Do not represent this wrapper as an official NASA website or as your own
implementation of NASA Eyes.
