# Aniket Chaware — Portfolio Website

## What's in this zip
```
index.html
assets/
  photo.jpg
  Aniket_Chaware_Resume.pdf
  figma.png, appsheet.png, appsscript.png, python.png, mysql.png,
  tableau.png, gworkspace.png, canva.png, excel.png, powerbi.png,
  jupyter.png, looker.png, github.png
```
`index.html` links to everything in `assets/` by a relative path
(e.g. `assets/photo.jpg`). **Keep the `assets` folder next to
`index.html` at all times** — if you move or upload the HTML file on
its own without that folder, the photo, resume, and logos will not
show up. This is the standard way real websites are structured (and
exactly how GitHub Pages / Netlify / Vercel expect it), so once
you host the whole folder together it will work correctly.

## Where to put it on your computer
Any folder is fine, e.g.:
```
D:\portfolio-website\aniket-website\index.html
D:\portfolio-website\aniket-website\assets\...
```
Double-click `index.html` (or open it in Chrome/Edge/Firefox) to
preview it locally — no server needed for that.

## If you ever want to update your photo, resume, or a logo
Just replace the matching file inside `assets/` with a new one of the
same filename (e.g. drop in a new `assets/photo.jpg`). No HTML editing
needed.

## How to put it online (pick one — all are free)

### Option A: GitHub Pages (recommended, free, your own domain-like URL)
1. Create a free GitHub account at github.com if you don't have one.
2. Create a new repository, e.g. `aniket-portfolio`.
3. Upload **both** `index.html` and the whole `assets` folder (GitHub's
   web UI "Add file → Upload files" lets you drag a folder in).
4. Go to the repo's **Settings → Pages**, set the source branch to `main`
   and the folder to `/ (root)`, then Save.
5. After a minute, your site will be live at:
   `https://<your-github-username>.github.io/aniket-portfolio/`

### Option B: Netlify (drag-and-drop, free)
1. Go to netlify.com and sign up (free).
2. On the dashboard, find "Deploy manually" / drag-and-drop area.
3. Drag the **whole folder** (containing `index.html` and `assets/`)
   into that area — not just the HTML file alone.
4. Netlify gives you a live URL immediately (e.g. `random-name.netlify.app`).

### Option C: Vercel
Same idea as Netlify — sign up at vercel.com, "Add New Project", upload
the folder, and it deploys instantly with a free `.vercel.app` URL.

### Custom domain (optional)
If you later buy a domain (e.g. `aniketchaware.com` from Namecheap/GoDaddy),
all three options above let you point that domain at your site for free —
just follow the "Custom domain" instructions in whichever host you pick.

## AI Assistant — how it actually works
Click the "AI Assistant" card (or the "Chat with AI Assistant" button) to
open a chat popup with an animated waving character. Type a question and
it replies about Aniket's experience, skills, projects, education, or
contact info.

**Important honesty note:** this is a *rule-based* assistant, not a live
LLM. It runs entirely in the visitor's browser and matches keywords in
their question against a small knowledge base built from Aniket's resume
— there's no real AI model, network call, or backend involved. A genuinely
LLM-powered assistant would need a server to hold an API key (a plain
HTML file can't safely store one), so this static site can't call a real
AI service without that extra piece of infrastructure. If you want a true
LLM-backed version later, the next step would be a small backend
(e.g. a serverless function) that calls an AI API and the site talks to
that instead — happy to help set that up when you're ready.

## Other notes
- The "Send a Message" form doesn't send anywhere yet — it's a visual demo.
  Wire it to Formspree, Web3Forms, or EmailJS (a few minutes of setup) if you
  want real messages to reach your inbox — happy to do that with you.
- Tech Stack logos: Python, MySQL, Excel, Power BI, Tableau, Google
  Workspace, Jupyter, Looker Studio, Figma, Canva, AppSheet, and Apps
  Script are your uploaded brand logo images. GitHub and LinkedIn tiles
  use your uploaded/real icons too.
