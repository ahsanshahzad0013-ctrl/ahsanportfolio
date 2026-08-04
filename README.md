# Ahsan Shahzad — Portfolio Website

## What's new in this update
- **About Me** section rewritten with your bio, 6 feature cards (AI Prompt
  Engineering, AI Videos, Website Development, AI Image Generation, Video
  Editing, AI Voice Content), and a "Let's Work Together" button that jumps
  to Contact.
- **My AI Videos** section added (after Portfolio) with 6 project cards:
  AI Short Film, AI Story Animation, AI Commercial Ad, AI Product Showcase,
  AI Explainer Video, AI Cinematic Scene. Two cards use real thumbnails from
  your uploaded images; the other four use gradient/icon placeholders until
  you have final video content.
- Everything else — Hero, Navigation, Services, Skills, Portfolio, Stats,
  Testimonials, Contact, Footer, theme, fonts, animations — is untouched.

## ⚠️ Important: this project now has TWO items, not one file
Earlier you only had to upload `index.html`. Now you must upload the whole
folder structure:
```
ahsan-portfolio-updated/
├── index.html
└── assets/
    └── images/
        ├── ai-commercial-ad-shoes.jpg
        └── ai-product-showcase-airpods.jpg
```
If you only upload `index.html` and skip the `assets` folder, those two
video thumbnails will show as broken images (everything else still works).

## Editing the AI Videos section yourself
Open `index.html` and search for:
```
EDIT-ZONE: AI VIDEO PROJECTS
```
Each project is one `<div class="avid-card glass"> ... </div>` block with
inline comments explaining how to swap the thumbnail, title, description,
tags, and the "Watch Video" link.

## Editing the About section yourself
Search for:
```
EDIT-ZONE: ABOUT ME
```
to update your bio text, the 6 feature cards, or the CTA button.

## Deploy (GitHub + Vercel)
1. Push **all files** (`index.html` and the `assets` folder) to your GitHub
   repo root — same level, not nested inside another folder.
2. On Vercel: Add New Project → import the repo → Framework preset **Other**
   → leave Build Command / Output Directory empty → Deploy.
3. Alternative: GitHub Pages via Settings → Pages → deploy from `main` /
   root.

If you ever see a 404 after deploying, it almost always means `index.html`
(and this time, the `assets` folder too) aren't sitting directly in the
repo root — check that first.
