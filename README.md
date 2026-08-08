# Lavender Town — Game Boy Viewer

GitHub/Vercel-ready static site for the Lavender Town 44 recovered screenshots.

## Repo structure

```text
index.html
package.json
vercel.json
public/
  gameboy.jpg
  1.png
  ...
  44.png
```

## Deploy through GitHub → Vercel

1. Create a new GitHub repo.
2. Upload/drag **the contents of this folder** into the repo root.
3. Commit to `main`.
4. In Vercel: **Add New Project** → import that GitHub repo.
5. Vercel should detect **Vite**.
6. Use:
   - Build Command: `npm run build`
   - Output Directory: `dist`
7. Deploy.

Controls: click/tap Game Boy buttons, swipe the screen, mouse wheel, arrow keys, or A/D keys.
