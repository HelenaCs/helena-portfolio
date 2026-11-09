# Helena Cadevall Soto · Portfolio

Portfolio of Helena Cadevall Soto, Product Designer and UX Researcher.

## Structure

```
index.html     the whole site: home, case studies and project pages
support.js     the runtime the page needs (keep it next to index.html)
assets/        images, fonts, PDFs (CV and thesis) and libraries
.nojekyll      tells GitHub Pages to serve the files as they are
```

## Publish on GitHub Pages

1. Create a public repository and upload the contents of this folder (not the folder itself) to its root.
2. Go to Settings > Pages > Build and deployment, choose "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
3. After a minute or two the site is live at `https://<username>.github.io/<repository>/`.
   If the repository is named `<username>.github.io`, the address is just `https://<username>.github.io/`.

## Preview locally

Open a terminal in this folder and run:

```
python3 -m http.server
```

Then open http://localhost:8000. Double-clicking index.html will not work, because the page loads its scripts as files.
