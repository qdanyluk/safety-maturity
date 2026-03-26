# Safety Culture Maturity Model — PWA

An interactive, evidence-based Safety Culture Maturity Model built as a Progressive Web App (PWA). Install it on your phone for offline access.

Based on Hudson (2001), Fleming (2001), Parker et al. (2006), and Gonçalves Filho et al. (2010), aligned with CSA Z45001 / ISO 45001.

---

## Files

```
safety-maturity-pwa/
├── index.html          ← Main app (interactive model)
├── manifest.json       ← PWA manifest (app name, icons, theme)
├── sw.js               ← Service worker (offline caching)
├── icons/
│   ├── icon.svg        ← Vector icon
│   ├── icon-192.png    ← 192×192 icon (Android/PWA)
│   └── icon-512.png    ← 512×512 icon (splash screen)
└── README.md           ← This file
```

---

## Deploy to GitHub Pages

### 1. Create a new GitHub repository

1. Go to [github.com/new](https://github.com/new)
2. Name it `safety-maturity` (or whatever you prefer)
3. Set it to **Public** (required for free GitHub Pages)
4. **Do not** initialize with a README (you already have one)
5. Click **Create repository**

### 2. Push the files

Open a terminal and run:

```bash
cd safety-maturity-pwa

git init
git add .
git commit -m "Initial commit - Safety Culture Maturity Model PWA"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/safety-maturity.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

### 3. Enable GitHub Pages

1. In your repository, go to **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Set branch to **main** and folder to **/ (root)**
4. Click **Save**
5. Wait 1–2 minutes for deployment

Your app will be live at:
```
https://YOUR_USERNAME.github.io/safety-maturity/
```

---

## Install on Your Phone

### Android (Chrome)
1. Open the GitHub Pages URL in Chrome
2. Tap the **three-dot menu** (⋮) → **Add to Home screen** (or you may see an install banner automatically)
3. Tap **Install**
4. The app icon will appear on your home screen

### iPhone (Safari)
1. Open the GitHub Pages URL in **Safari** (must be Safari)
2. Tap the **Share** button (□↑)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add**
5. The app icon will appear on your home screen

Once installed, the app works offline — no internet connection needed after the first load.

---

## Updating the App

After making changes to any files:

```bash
git add .
git commit -m "Description of changes"
git push
```

GitHub Pages will automatically redeploy within 1–2 minutes.

If the app is already installed on your phone, open it once while connected to the internet to pull the latest version. You may need to close and reopen the app for changes to take effect.
