# ⭐ Star Learner

A child-friendly Progressive Web App (PWA) for practising maths, tricky words, and number neighbours. Works offline and can be installed to an iPad or phone home screen like a native app.

---

## 📁 Files in this folder

```
star-learner/
├── index.html          ← The whole app
├── manifest.json       ← PWA config (name, icon, colours)
├── sw.js               ← Service worker (offline caching)
├── README.md           ← This file
└── icons/
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    ├── icon-512x512.png
    ├── apple-touch-icon.png
    ├── favicon-32x32.png
    └── favicon.ico
```

---

## 🚀 Publishing to GitHub Pages (free, ~5 minutes)

### Step 1 — Create a GitHub account
Go to **https://github.com** and sign up (free). Skip if you already have one.

### Step 2 — Create a new repository
1. Click the **＋** button (top right) → **New repository**
2. Name it exactly: `star-learner`
3. Set it to **Public**
4. Leave everything else as default
5. Click **Create repository**

### Step 3 — Upload your files
1. On the next screen click **uploading an existing file**
2. Drag the entire `star-learner` folder contents into the upload area:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - The `icons/` folder (drag the whole folder)
3. Scroll down, click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Click **Settings** (top of your repo page)
2. Click **Pages** in the left sidebar
3. Under **Source**, choose **Deploy from a branch**
4. Set Branch to **main**, folder to **/ (root)**
5. Click **Save**
6. Wait ~60 seconds, refresh — you'll see:
   > Your site is live at **https://YOUR-USERNAME.github.io/star-learner/**

---

## 📱 Installing on iPad / iPhone

1. Open **Safari** on the iPad
2. Go to your URL: `https://YOUR-USERNAME.github.io/star-learner/`
3. Tap the **Share** button (the box with an arrow pointing up)
4. Scroll down and tap **"Add to Home Screen"**
5. Tap **Add** — the Star Learner icon appears on the home screen!
6. Open it from the home screen — it runs full-screen, no browser bar ✓

> **Tip:** The app caches itself after first load, so it works offline (on a plane, no Wi-Fi, etc.)

## 📱 Installing on Android

1. Open **Chrome** on the Android device
2. Go to your URL
3. A banner will appear at the bottom: **"Add Star Learner to home screen"** — tap it
4. Or tap the ⋮ menu → **Add to Home screen**

---

## 🔐 Teacher password
Default password: **teacher123**

---

## 🔄 Updating the app
When you make changes to the files, just re-upload them to GitHub (drag and drop again into the repo). GitHub Pages updates automatically within a minute or two.

To clear the app cache on a device after an update: close and reopen the app, or go to Settings → Safari → Clear Website Data.
