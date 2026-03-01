# 🌡️ Pool Heat Cool Unit Sizing — Heater & Chiller Selection Tool

**Professional swimming pool heat pump sizing tool for engineers & contractors in UAE & Middle East**

> Calculates heating and cooling loads using the FLUIDRA methodology and automatically selects the best-fit unit from leading brands.

---

## 🌐 Live Site

**https://jit8jit-arch.github.io/pool-heat-cool-pump-sizing/**

---

## 🏷 Brands Covered

| Brand | Series | Models |
|-------|--------|--------|
| AQUA Middle East | PH2 Series (60Hz) | 15 models |
| AQUATECH | WM018 → WM1000 | 17 models |
| PROTEAM Europa | Standard Heat & Chill (005xxxxx) | 20 models |
| PROTEAM Europa | Inverter Heat Chill (006xxxxx) | 15 models |
| Fluidra / AstralPool | AHP Series | 10 models |

---

## 🚀 How to Deploy on GitHub Pages (Step-by-Step)

### Step 1 — Create a GitHub Account
Go to **https://github.com** and sign up (free).

### Step 2 — Create a New Repository
1. Click the **+** icon → **New repository**
2. Name it: `pool-heat-cool-pump-sizing`
3. Set to **Public**
4. Click **Create repository**

### Step 3 — Upload the File
1. Click **uploading an existing file**
2. Drag and drop `index.html` into the upload area
3. Scroll down → click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repository → **Settings** tab
2. Left sidebar → **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Branch: **main** | Folder: **/ (root)**
5. Click **Save**

### Step 5 — Your site is live!
Wait 1–2 minutes, then visit:
```
https://jit8jit-arch.github.io/pool-heat-cool-pump-sizing/
```

---

## 💰 How to Add Google AdSense

### Step 1 — Apply for AdSense
1. Go to **https://www.google.com/adsense**
2. Sign in with your Google account
3. Enter your website URL: `https://jit8jit-arch.github.io/pool-heat-cool-pump-sizing/`
4. Submit application — Google reviews in 1–14 days

### Step 2 — Get Your Publisher ID
After approval, your Publisher ID looks like:
```
ca-pub-1234567890123456
```

### Step 3 — Activate AdSense in the HTML
Open `index.html` and find these two commented-out blocks:

**Block 1** (in the `<head>` section) — remove the `<!--` and `-->`:
```html
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
```

**Block 2** (bottom of page, before footer) — remove the `<!--` and `-->` and replace IDs:
```html
<ins class="adsbygoogle"
     data-ad-client="ca-pub-YOUR-PUBLISHER-ID"
     data-ad-slot="YOUR-AD-UNIT-ID"
     ...></ins>
```

### Step 4 — Update `index.html` on GitHub
1. Go to your repository
2. Click `index.html` → pencil icon ✏️ to edit
3. Make changes → **Commit changes**
4. Site updates automatically in ~1 minute

---

## 📋 AdSense Requirements Checklist

- [x] Original, useful content ✅
- [x] Privacy Policy included ✅ (in the footer)
- [ ] Sufficient traffic (build audience first)
- [ ] Site must be live for at least a few weeks before applying
- [ ] Add your real contact email in the footer

---

## 🛠 Customisation

### Change the contact email
Search for `info@aquacalc.com` and replace with your email.

### Change the site name
Search for `Pool Heat Cool Unit Sizing` and replace with your preferred brand name.

### Update the canonical URL
Search for `jit8jit-arch` and replace with your actual GitHub username everywhere.

### Add your own brand logo
Replace the `⚡ AQUACALC` text in the footer with an `<img>` tag pointing to your logo.

---

## 📁 File Structure

```
aquacalc/
├── index.html        ← Main calculator (everything is in one file)
└── README.md         ← This file
```

That's it — single file, no dependencies, no build step needed.

---

## ⚠️ Disclaimer

All technical data is sourced from manufacturer datasheets and is provided for reference only.
Results are for guidance only. Always verify with manufacturer datasheets and a qualified engineer before equipment procurement.

---

*Built for pool industry professionals in UAE & Middle East.*
