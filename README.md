# Ahsan Shahzad — Portfolio Website

A single-file, production-ready portfolio site (HTML + CSS + JS all in `index.html`).

## What's inside
- Hero with animated typing effect + live "prompt console" animation
- About, Services, Skills, Portfolio (with filtering), Stats (animated counters),
  Testimonials, Contact form, and Footer sections
- Neural-network particle background, glassmorphism cards, scroll reveal animations
- Fully responsive (mobile, tablet, desktop)

## Before you deploy — update these placeholders
1. **Profile photo**: Currently shows your initials "AS" in a gradient ring.
   To use a real photo, add your image file to this folder and in `index.html` replace:
   ```html
   <div class="avatar-inner">
     <span class="avatar-initials">AS</span>
   </div>
   ```
   with:
   ```html
   <div class="avatar-inner">
     <img src="your-photo.jpg" alt="Ahsan Shahzad">
   </div>
   ```
2. **Email**: Search for `hello@ahsanshahzad.dev` in `index.html` (appears twice —
   Contact section and the mailto script) and replace with your real email.
3. **Social links**: In the Contact section and Footer, replace the `#` placeholder
   `href` values for LinkedIn, Fiverr, and YouTube with your real profile URLs.
   The GitHub link is already set to your real profile.

## Deploy to GitHub + Vercel

### 1. Push to GitHub
```bash
cd ahsan-portfolio
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/ahsanshahzad0013-ctrl/ahsan-portfolio.git
git push -u origin main
```
(Create an empty repo named `ahsan-portfolio` on GitHub first — don't initialize it
with a README, so this push doesn't conflict.)

### 2. Deploy on Vercel
- Go to vercel.com → **Add New Project**
- Import the `ahsan-portfolio` repo from GitHub
- Framework preset: **Other** (plain HTML, no build step)
- Leave Build Command and Output Directory empty
- Click **Deploy**

You'll get a live URL like `ahsan-portfolio.vercel.app` within about a minute.

### Alternative: GitHub Pages
- In the repo, go to **Settings → Pages**
- Source: `main` branch, `/ (root)` folder
- Save — your site will be live at `https://ahsanshahzad0013-ctrl.github.io/ahsan-portfolio/`
