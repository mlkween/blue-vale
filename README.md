# The Color of the Song — a Choose-Your-Own-Adventure

An interactive gift: a branching Choose-Your-Own-Adventure through the world of
FFXIV. Choices matter — kindness, patience, and staying *together* lead onward,
while a poor choice ends the run early (a wrong turn drops you back to the start
of that chapter to try again). Only the true path earns the grand reveal of the
commissioned artwork of the two friends in the field of blue flowers; other
endings show just a blurred blue glimpse to pull you back in.

## Files
```
blue-vale-game/
├── index.html          ← the whole game (open this to play)
├── assets/
│   ├── blue-field.jpg  ← the commissioned artwork (final reveal)
│   └── blue-field-tiny.jpg
└── README.md           ← this file
```

## ▶ To personalise it (2 minutes)
Open `index.html` in any text editor and find the **CONFIG** block near the top of
the `<script>` (it's clearly marked). Edit these:

- `bridesmaidName` — your bridesmaid's real name (shown only on the final screen)
- `yourName` — your name
- `showBirthday` — `true` or `false`
- `finaleLead` — the line just before the artwork fades in
- `finaleMessage` — your personal note (each paragraph wrapped in `<p>…</p>`)
- `signOff` — how you sign off

The story itself uses the characters' names (Nazuna & Vaelira) throughout — the real
names appear only at the end.

## ▶ To preview locally
Just double-click `index.html` — it opens in your browser, no setup needed.

## ▶ To host it free on GitHub Pages
1. Create a new repository on GitHub (e.g. `blue-vale`). Make it **Public**.
2. Upload the **contents** of this `blue-vale-game` folder to the repo
   (so `index.html` sits at the top level of the repo, with the `assets/` folder
   beside it). You can drag-and-drop the files in GitHub's "Add file → Upload files".
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source: Deploy from a branch**, then choose
   **Branch: `main`** and **Folder: `/ (root)`**. Click **Save**.
5. Wait ~1 minute. Your game will be live at:
   `https://<your-github-username>.github.io/<repo-name>/`
6. Send that link to your bridesmaid. 💙

Tip: if the page loads but the final image doesn't, double-check the `assets` folder
was uploaded and that the file is named exactly `blue-field.jpg`.

## Notes
- The reveal image here is web-optimised (~500 KB). Keep your original full-resolution
  artwork file safe for printing — this copy is just for the web.
- Works on phones and desktop.
