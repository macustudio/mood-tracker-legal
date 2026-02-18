# Publish to GitHub Pages

When you're ready (after logging in to GitHub), do this:

## 1. Create the repo

- Go to **https://github.com/new**
- Repository name: `mood-tracker-legal`
- Public, no README
- Create repository

## 2. Upload these files

**Option A — Drag & drop (easiest)**

1. On the new repo page, click **"uploading an existing file"**
2. Drag the 4 files from this folder into the browser:
   - `index.html`
   - `privacy-policy.html`
   - `terms-of-service.html`
3. Click **Commit changes**

**Option B — Git**

```bash
cd /path/to/FirstApp/mood-tracker-legal
git init
git add .
git commit -m "Add legal pages"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/mood-tracker-legal.git
git push -u origin main
```

## 3. Enable GitHub Pages

1. Repo → **Settings** → **Pages** (left sidebar)
2. **Source:** Deploy from a branch
3. **Branch:** `main` / `/(root)` → **Save**
4. Wait 1–2 minutes

## 4. Your URLs

- **Privacy Policy (for App Store):**  
  `https://YOUR_USERNAME.github.io/mood-tracker-legal/privacy-policy.html`

- **Terms:**  
  `https://YOUR_USERNAME.github.io/mood-tracker-legal/terms-of-service.html`

- **Root (redirects to Privacy):**  
  `https://YOUR_USERNAME.github.io/mood-tracker-legal/`

## 5. App Store Connect

Paste the Privacy Policy URL in **App Store Connect** → **App Information** → **Privacy Policy URL**.
