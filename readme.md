# muzhaqi.com

Portfolio of Artan (Tani) Muzhaqi. Live at [muzhaqi.com](https://muzhaqi.com).

Hand-written HTML and CSS with no build step and no JavaScript. GitHub Pages serves `master` from the repo root, so pushing to `master` deploys.

## Preview locally

```bash
python3 -m http.server 4173
```

Asset paths start at the site root, so open `http://127.0.0.1:4173/` rather than the file directly.

## Layout

| Path | What it is |
| --- | --- |
| `index.html` | The whole site |
| `404.html` | Not found page |
| `styles/main.css` | All styles. Theme colors are the custom properties at the top |
| `fonts/` | Self-hosted Bricolage Grotesque and DM Mono (SIL OFL), Latin subsets |
| `images/` | AVIF and WebP pairs. Sous Chef screens come from the demo account |

## Résumé

The résumé lives at [cv.muzhaqi.com/amuzhaqi/artan-muzhaqi](https://cv.muzhaqi.com/amuzhaqi/artan-muzhaqi). To update it, edit it in Reactive Resume. Don't keep an export in this repo: every file here is published, and exports include the phone number.

## Keeping it accurate

LinkedIn is the reference for job history, dates, skills and certifications. Sous Chef is a side project, so it stays under Projects. Its figures on the site are counted from the code, so recount them before changing them.
