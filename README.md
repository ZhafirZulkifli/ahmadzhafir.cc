# Dr. Ahmad Zhafir Zulkifli - Modernized Website Portal

A modern, high-performance personal landing portal designed for **Dr. Ahmad Zhafir Zulkifli** (Medical Doctor & Public Health Professional).

---

## ✨ Features & Upgrades Over the Legacy Site

1. **Executive Aesthetics & Modern UI**:
   - Replaced uniform vertical block buttons with an organized, categorized hub.
   - Refined portrait display with an active status badge.
   - Built with **Plus Jakarta Sans** and **Amiri** (for the Arabic reflection).
   - Glassmorphism surfaces, subtle ambient background glow, and smooth micro-interactions.

2. **Categorized Architecture**:
   - 🎓 **Academic & Research**: Highlighted ORCID ID (`0009-0003-7369-2685`), ResearchGate profile, and Slide deck presentations.
   - ✍️ **Blog & Writings**: Prominent callout card for `blog.ahmadzhafir.cc`.
   - 🕊️ **Guiding Principle**: Dignified presentation of the Hadith from Ibn Umar on mortality and purpose in bilingual Arabic/English format.
   - 🌐 **Connect Hub**: Clean social and professional links (LinkedIn, GitHub, YouTube, Facebook, Email, Buy Me a Coffee).
   - 📍 **Footer Roots**: Highlights Dr. Zhafir's career footprints across Jerantut, Temerloh, Serian, Shah Alam, Sungai Buloh, and Malaysia.

3. **Performance & Standards**:
   - 🌓 **Dark & Light Mode Switcher** with automatic system preference detection and `localStorage` persistence.
   - 📋 **One-click Copy Email** with toast notification feedback.
   - 📱 **Fully Responsive**: Mobile-first design that looks crisp on phones, tablets, and wide monitors.
   - ⚡ **Zero Dependencies**: Pure HTML5, CSS3, and vanilla JS (< 50KB total). No frameworks or build steps required.

---

## 🚀 How to Preview Locally

Double click [`index.html`](file:///C:/Users/ZHAFIR/.gemini/antigravity/scratch/ahmadzhafir-website/index.html) or run in PowerShell:

```powershell
Start-Process "C:\Users\ZHAFIR\.gemini\antigravity\scratch\ahmadzhafir-website\index.html"
```

---

## 🌐 Free 1-Click Deployment Options for `www.ahmadzhafir.cc`

### Option 1: GitHub Pages (Recommended)
Since you already have a GitHub account (`github.com/ZhafirZulkifli`):

1. Create a repository on GitHub named `ahmadzhafir.cc` or `ZhafirZulkifli.github.io`.
2. Push the files in this directory (`index.html`, `styles.css`, `script.js`).
3. In repository **Settings** → **Pages**:
   - Source: Deploy from branch `main` / `root`.
   - Custom domain: enter `www.ahmadzhafir.cc`.
   - Check **Enforce HTTPS**.
4. In your domain DNS (where you manage `ahmadzhafir.cc`):
   - Add a CNAME record: `www` points to `<your-username>.github.io`.

### Option 2: Cloudflare Pages
1. Log in to [dash.cloudflare.com](https://dash.cloudflare.com) → **Workers & Pages**.
2. Click **Create Application** → **Pages** → **Direct Upload**.
3. Drag & drop the `ahmadzhafir-website` folder.
4. Attach your custom domain `www.ahmadzhafir.cc`. Cloudflare handles SSL automatically with worldwide CDN caching.
