# Vedika Pandey — Portfolio

Personal portfolio website for Vedika Pandey, Sustainability Consultant.

## Live site

Deployed via GitHub Pages: `https://<your-github-username>.github.io/<repo-name>/`

## How to deploy

### 1. Create a GitHub repository

1. Go to [github.com](https://github.com) and sign in
2. Click **New repository**
3. Name it anything (e.g. `portfolio` or `vedika-pandey`)
4. Set it to **Public**
5. Click **Create repository**

### 2. Upload the files

**Option A — via the GitHub website (simplest):**
1. On your new repo page, click **Add file → Upload files**
2. Drag and drop all files from this folder (`index.html`, `README.md`, `.nojekyll`)
3. Click **Commit changes**

**Option B — via Git (terminal):**
```bash
git init
git add .
git commit -m "Initial portfolio deploy"
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Choose branch: `main`, folder: `/ (root)`
4. Click **Save**

Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire portfolio — fully self-contained (all images embedded) |
| `README.md` | This file |
| `.nojekyll` | Tells GitHub Pages to skip Jekyll processing (prevents build issues) |

## Updating the site

Edit `index.html` and push/upload the updated file. Changes go live within ~30 seconds.
