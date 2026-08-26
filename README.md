# Motlatsi Seema — Portfolio Website

A single-page, responsive portfolio site for Motlatsi Seema (Cybersecurity Analyst, Ethical Hacker, Data Analyst).

## Files
- `index.html` — the whole site (HTML/CSS/JS in one file, no build step needed)
- `assets/motlatsi-seema-cv.pdf` — downloadable CV, linked from the "Download CV" button

## Before you deploy — 2 things to fill in
Open `index.html`, find the Contact section near the bottom, and replace the two placeholder links:
```html
<a href="#" aria-label="Add your GitHub profile link"><span class="k">GitHub</span> Add your GitHub link</a>
<a href="#" aria-label="Add your LinkedIn profile link"><span class="k">LinkedIn</span> Add your LinkedIn link</a>
```
Swap the `href="#"` for your real GitHub and LinkedIn URLs, and update the visible text too.

## How to deploy (pick one — all are free)

### Option 1: Netlify (easiest, drag-and-drop)
1. Go to https://app.netlify.com/drop
2. Drag the whole folder (containing `index.html` and `assets/`) into the browser window
3. Netlify gives you a live URL instantly — you can rename it in Site settings

### Option 2: Vercel
1. Create a free account at https://vercel.com
2. Install the CLI: `npm i -g vercel`
3. In this folder, run `vercel` and follow the prompts

### Option 3: GitHub Pages
1. Create a new GitHub repository (e.g. `portfolio`)
2. Push these files to it:
   ```
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/portfolio.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**, set source to the `main` branch, root folder
4. Your site will be live at `https://<your-username>.github.io/portfolio`

## For your project submission
- **Live deployed site**: the URL from whichever option above you choose
- **Source code/repository**: push this folder to GitHub (see Option 3) and share the repo link
- **PowerPoint presentation**: let me know if you'd like help building this next — I can summarise the site, your design decisions, and the tech stack into slides.
