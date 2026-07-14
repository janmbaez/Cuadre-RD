# CuadreRD Website

Static GitHub Pages-ready website for CuadreRD, an iOS personal finance app for users in the Dominican Republic.

The site includes:

- `index.html` - public application homepage
- `privacy.html` - public Privacy Policy
- `terms.html` - public Terms of Service
- `styles.css` - shared responsive styling
- `script.js` - small navigation and animation enhancements
- `assets/` - lightweight visual assets

## 1. Open the Site Locally

No backend, framework, or build step is required.

Open `index.html` directly in your browser:

```text
index.html
```

You can also run a simple local static server from this folder:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000/
```

## 2. Upload to GitHub

Create a new GitHub repository, then upload these files to the repository root:

```text
index.html
privacy.html
terms.html
styles.css
script.js
README.md
assets/
```

If you are using git from the command line:

```bash
git init
git add .
git commit -m "Add CuadreRD public website"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

## 3. Enable GitHub Pages

1. Open your repository on GitHub.
2. Go to **Settings**.
3. Select **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder.
6. Save the settings.

GitHub will publish the website after the Pages deployment finishes.

## 4. Google Cloud OAuth URLs

Use these public URLs in Google Cloud OAuth app settings after GitHub Pages is enabled:

```text
Homepage URL: https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/
Privacy Policy URL: https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/privacy.html
Terms of Service URL: https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/terms.html
```

Replace `YOUR_GITHUB_USERNAME` and `YOUR_REPO_NAME` with your actual GitHub username and repository name.
