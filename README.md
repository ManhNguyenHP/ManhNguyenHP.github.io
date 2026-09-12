# manhnguyenhp.github.io

Personal portfolio of **Nguyen Duc Manh** — B.Sc. Mathematics &amp; Informatics, Hanoi University of
Science and Technology. Machine learning, physics-informed neural networks, agentic AI and applied
mathematics.

**Live site:** https://manhnguyenhp.github.io/

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | The whole site. Self-contained: no build step, no dependencies, no external requests. |
| `CV_NguyenDucManh.pdf` | Downloadable CV, linked from the hero and the footer. |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is. |

## Features

- **Bilingual** — English and Vietnamese, toggled by the `VI` / `EN` button. The choice is remembered in `localStorage`.
- **Light and dark** — follows the operating system by default, overridable with the `◐` button.
- **Responsive** — single column from roughly 400px upwards.
- **Zero dependencies** — one HTML file with inline CSS and JavaScript, so it loads instantly and never breaks when a CDN changes.

## Editing

Open `index.html` and edit directly. Translatable content is paired: every English fragment sits in a
`<span class="en">` next to its Vietnamese `<span class="vi">` counterpart, and the language switch
only changes which class is visible. When you add a sentence, add both versions.

Colours, spacing and typography live in the `:root` custom properties at the top of the `<style>`
block. The dark palette is redefined twice, once under `prefers-color-scheme` and once under
`[data-theme="dark"]`, so the manual toggle wins in both directions.

## Deployment

GitHub Pages serves the `main` branch root. Push to `main` and the site rebuilds within a minute.

```bash
git add -A
git commit -m "Update portfolio"
git push
```

## Contact

- Email — manh.nd2824@gmail.com
- LinkedIn — https://www.linkedin.com/in/manh-nguyen-duc-68753b322
