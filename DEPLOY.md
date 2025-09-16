# Deploying to GitHub Pages

Follow these steps to publish this portfolio at `mahigurjarr.github.io`.

## 1. Create the Repository
- Sign in to GitHub and create a new public repository named `mahigurjarr.github.io`.
- Leave it empty (no README, .gitignore, or license) so you can push this project directly.

## 2. Add the Remote & Push Code
Inside this project folder:
```bash
git init
git branch -M main
git remote add origin https://github.com/Mahigurjarr/mahigurjarr.github.io.git
git add README.md index.html style.css DEPLOY.md
git commit -m "Setup portfolio site"
git push -u origin main
```
If the repository already exists with commits, just add the remote and push: `git remote add origin ...` followed by `git push`.

## 3. Enable GitHub Pages
- Open the repository on GitHub.
- Go to **Settings → Pages**.
- Under **Source**, choose the `main` branch and the `/ (root)` folder, then click **Save**.
- GitHub will build the site in a few minutes. Your site will be live at `https://mahigurjarr.github.io`.

## 4. Add the Link to Your GitHub Bio
- Navigate to your GitHub profile settings.
- Paste `https://mahigurjarr.github.io` into the **Website** field under **Profile** and save.
- Optionally add a short tagline referencing the new portfolio in your bio.

🎉 That’s it! Each time you update `index.html` or `style.css`, run `git add`, `git commit`, and `git push` to publish the changes automatically.
