# Redekop x SeedMaster - Australia landing page

Single self-contained page (`index.html`). All fonts, logos and photography are inlined, so nothing else is required to serve it.

## Publish with GitHub Pages

1. Create a new repository on github.com (public), e.g. `redekop-seedmaster-au`.
2. Upload the contents of this folder to the repository root ("Add file" > "Upload files", drag in `index.html`, commit).
3. In the repo: **Settings > Pages**.
4. Under "Build and deployment", set Source = **Deploy from a branch**, Branch = **main**, folder = **/ (root)**. Save.
5. Wait about a minute. The page goes live at `https://<your-username>.github.io/<repo-name>/`.

### Custom domain (optional)
In Settings > Pages > Custom domain, enter e.g. `seedmaster.redekopmfg.com`, then add a CNAME record at your DNS provider pointing that hostname to `<your-username>.github.io`.

### Command line alternative
```bash
git init
git add index.html README.md
git commit -m "Redekop x SeedMaster Australia landing page"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```
Then follow steps 3-5 above.

## Updating
Replace `index.html` with a newly exported file and commit. Pages redeploys automatically.
