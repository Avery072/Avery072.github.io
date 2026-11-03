# renpei cai [chai] — portfolio

Plain static site: `index.html` + `resume.pdf`. No build step.

## Deploy on GitHub Pages
1. Create a repo named `Avery072.github.io`.
2. Upload `index.html` and `resume.pdf` (and an `img/` folder if you add images).
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site goes live at https://avery072.github.io in a minute or two.

## Or Vercel / Netlify
Drag this folder into the dashboard. That's it.

## To fill in
- **Your photo:** save a portrait (roughly 4:5) as `img/me.jpg`. It appears in the hero automatically.
- **Mix link:** search `latest mix` in `index.html` and replace `href="#"` with your SoundCloud/Mixcloud URL.
- **Project screenshots:** put images in `img/` and add `<img src="img/name.jpg" alt="">` inside a `.cover` div.
- **Research frames:** same idea inside each `.frame` div. A muted looping clip works too:
  `<video src="img/orbit.mp4" autoplay muted loop playsinline></video>`
- **Resume:** replace `resume.pdf` whenever you update it (keep the filename).
