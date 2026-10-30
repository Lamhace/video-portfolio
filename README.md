# Ojo Oladimeji — video editing portfolio

Static site: `index.html` + `videos/` + `posters/`. No build step.

## Deploy (GitHub + Vercel)
1. Create a new GitHub repo (e.g. `video-portfolio`) and upload everything in this folder.
2. Go to vercel.com → Add New → Project → import the repo.
3. Framework preset: **Other**. Leave build command empty. Click Deploy.
4. Optional: in Project → Settings → Domains, rename it to something like `ojo-edits.vercel.app`.

## Adding a new Short
1. Compress it (about 720×1280, under 10 MB) and put it in `videos/`.
2. Save a still frame as a .jpg in `posters/`.
3. Copy one `<figure class="clip">…</figure>` block in `index.html` and change the file names, title and description.
