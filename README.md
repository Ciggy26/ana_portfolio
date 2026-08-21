# Ana Mićanović, Game Producer Portfolio

Static one-pager, no build step required.

## Deploy on GitHub Pages
1. Push this repo's contents to a GitHub repository (root, or a `docs/` folder).
2. Repo → Settings → Pages → Source: select the branch (and `/root` or `/docs`).
3. Site goes live at `https://<username>.github.io/<repo>/`.

## Structure
```
index.html
assets/
  portrait.jpg              → hero photo
  nsg/astronaut.webp        → negativespace portal asset
  nsg/mark.webp             → negativespace portal asset
  projects/revolve.jpg      → cropped from original project documentation
  projects/grimm-grimmer.jpg
  projects/reformation.jpg
  projects/flora-forge.jpg
  projects/razlog.jpg
```

## Open items
- Project images are cropped from the original project documentation/decks
  (Revolve, Grimm & Grimmer, Re:Formation, Flora Forge) and from the old
  portfolio deck (Raz.log, formerly "Project Hammerfall"). All five are
  displayed in grayscale via CSS (`.thumb img{filter:grayscale(1) ...}`) to
  match the rest of the page. Swap in higher-res or better-framed shots any
  time by replacing the files in `assets/projects/` (same filenames), or
  switch to color by removing that filter rule.
