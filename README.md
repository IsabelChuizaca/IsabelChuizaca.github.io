# IsabelChuizaca.github.io — redesign

A lightweight static redesign for Isabel Chuizaca's academic/research portfolio.

## What changed

The previous repository uses HugoBlox / Hugo Academic CV. This redesign intentionally simplifies the site to a static GitHub Pages structure:

- `index.html`
- `styles.css`
- `script.js`
- `assets/`

No Hugo, Go, npm or build process is required.

## Before publishing

1. Replace `assets/profile-placeholder.svg` with Isabel's preferred portrait. You can either keep the same filename or update the `<img src>` in `index.html`.
2. Add the CV as `assets/Isabel-Chuizaca-CV.pdf`.
3. Add Isabel's preferred professional email in the Contact section.
4. Review the skills list and remove anything she does not want to claim publicly.
5. Review publication links and add DOI/project links as desired.

## Publish on GitHub Pages

If this replaces the current contents of `IsabelChuizaca/IsabelChuizaca.github.io`:

1. Back up the current branch.
2. Remove the old Hugo files if you want the repository to stay minimal.
3. Copy these files to the repository root.
4. Commit and push to `main`.
5. In GitHub: **Settings → Pages → Deploy from a branch → main / (root)**.

The user site should then be available at `https://isabelchuizaca.github.io/`.

## Local preview

Open `index.html` directly in a browser, or run a simple local server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Notes

The content was adapted from publicly visible professional/academic information. Isabel should approve the final wording before publication.
