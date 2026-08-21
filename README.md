# rivimal.github.io

Personal academic and research website for **Chathuranga Liyanage**.

## Publish this site on GitHub Pages

Because the GitHub username is `rivimal`, the repository must be named exactly:

`rivimal.github.io`

Then the public website address will be:

`https://rivimal.github.io/`

### Option A — Upload using GitHub website

1. Sign in to GitHub.
2. Create a **new public repository** named `rivimal.github.io`.
3. Do **not** add a README/license/gitignore when creating it if you plan to upload this folder as-is.
4. Upload all files and folders from this package to the repository root.
5. Commit the files.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select branch **main** and folder **/(root)**, then Save.
9. Wait a few minutes and visit `https://rivimal.github.io/`.

### Option B — Push with Git

```bash
git init
git add .
git commit -m "Create personal academic website"
git branch -M main
git remote add origin https://github.com/rivimal/rivimal.github.io.git
git push -u origin main
```

Then enable GitHub Pages in **Settings → Pages** using `main` / `/(root)` if it is not already active.

## Update later

- Main page: `index.html`
- Styling: `assets/css/styles.css`
- Small menu/year script: `assets/js/main.js`
- Academic CV: `assets/docs/Chathuranga_Liyanage_CV.pdf`

Edit, commit, and push changes. GitHub Pages will redeploy the site.

## Privacy note

This public version intentionally does not publish private CV details such as full home address, date of birth, phone number, or referee contact details.
