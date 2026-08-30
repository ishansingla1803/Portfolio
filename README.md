# Ishan — Portfolio

A single-page portfolio site. No build tools needed — it's just one `index.html` file.

## What to edit before you publish

Open `index.html` in any text editor (VS Code recommended) and search for these:

1. **Contact links** — find `<!-- PLACEHOLDER: replace each href with your real links -->`
   near the bottom, and swap in your real Email, GitHub, LinkedIn, LeetCode URLs.
2. **Calculator project link** — find `<!-- PLACEHOLDER: replace # with your GitHub repo / live link -->`
   and add your repo's URL.
3. **Sensor project link** — optional, add a link or delete the `<a>` line if you don't have one.
4. **Certifications** — the "Certifications & achievements" section has 3 dashed placeholder
   boxes. Once you have certificates, replace a `.cert-slot` div with a real card (copy the
   style of a `.project-card` if you want it to show an image/link).
5. **"Currently learning" chips** — feel free to remove "C++ (OOP & DSA)" if you don't want
   that listed yet, or add more.

## How to deploy it

### Option A: Vercel (easiest)
1. Go to [vercel.com](https://vercel.com) and sign up/log in with GitHub.
2. Click **Add New → Project**, then **Deploy** (or drag-and-drop the folder if you don't
   want to use GitHub — Vercel supports drag-and-drop deploys too).
3. You'll get a live link like `ishan.vercel.app`.

### Option B: Netlify
1. Go to [netlify.com](https://netlify.com) and sign up/log in.
2. Drag the folder containing `index.html` onto the Netlify dashboard ("Deploys" tab).
3. You'll get a live link instantly.

### Option C: GitHub Pages (free, tied to your GitHub)
1. Create a new GitHub repo, e.g. `portfolio`.
2. Upload `index.html` to it (rename nothing — GitHub Pages looks for `index.html`).
3. Go to repo **Settings → Pages**, set source to `main` branch, root folder.
4. Your site will be live at `https://<your-username>.github.io/portfolio/`.

Any of the three work well — Vercel/Netlify are fastest to set up, GitHub Pages keeps
everything inside your GitHub account (nice since you're already deploying projects there).
