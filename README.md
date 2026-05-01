# Upama Upadhyay — Portfolio Website

A professional portfolio website for Upama Upadhyay, Principal Data Analyst at NielsenIQ (GfK).

## 🌐 Live Demo
Deploy to GitHub Pages and your site will be live at:
`https://<your-username>.github.io/<repo-name>/`

---

## 📁 Project Structure

```
portfolio/
├── index.html          ← Main entry point
├── css/
│   └── style.css       ← All styles (dark theme, animations, responsive)
├── js/
│   └── main.js         ← Cursor, scroll reveal, counters, typed text
├── images/
│   └── upama.png       ← Profile photo
└── README.md           ← This file
```

---

## 🚀 Deploying to GitHub Pages

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click **New repository**
3. Name it `portfolio` (or any name you prefer)
4. Set to **Public**
5. Click **Create repository**

### Step 2 — Upload Files
**Option A — GitHub Web UI (easiest):**
1. Open the repo on GitHub
2. Click **Add file → Upload files**
3. Drag and drop all files maintaining the folder structure:
   - `index.html` (root)
   - `css/style.css`
   - `js/main.js`
   - `images/upama.png`
4. Commit the changes

**Option B — Git CLI:**
```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll to **Pages** in the left sidebar
4. Under **Source**, select `Deploy from a branch`
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**
7. Wait 2–5 minutes, then visit your site at the URL shown

---

## ✨ Features
- **Dark luxury theme** with gold accents
- **Custom cursor** with smooth ring follow effect
- **Typed role animation** in hero section
- **Animated counters** (years, team size, delivery improvement)
- **Scroll reveal** animations on all sections
- **NIQ Pipeline diagram** — visual step-by-step workflow
- **Timeline** experience section with hover effects
- **Awards section** with all 3 NielsenIQ awards
- **Contact form** with success state
- **Fully responsive** — mobile, tablet, desktop
- **Zero dependencies** — pure HTML/CSS/JS, no frameworks needed

---

## 🛠 Customisation

### Update Contact Info
Edit `index.html` — search for `upamaupadhyay@gmail.com` and `7906777129`

### Change Colors
Edit `css/style.css` — modify the `:root` CSS variables at the top:
```css
:root {
  --gold:  #c9a84c;  /* Primary accent */
  --blue:  #4a90d9;  /* Secondary accent */
  --teal:  #3ecfb2;  /* Tertiary accent */
  --bg:    #0a0e17;  /* Main background */
}
```

### Add/Edit Experience
In `index.html`, find the `#experience` section and add new `.timeline-item` blocks following the existing pattern.

---

## 📱 Browser Support
Chrome, Firefox, Safari, Edge — all modern browsers. IE not supported.

---

Built with ❤️ — May 2026
