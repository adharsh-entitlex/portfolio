# Adharsh M. — Personal Portfolio

A premium editorial single-page portfolio built with plain HTML, CSS and JavaScript. No build step, no dependencies.

## Preview locally
Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 3000
```

## Publish free with GitHub Pages
1. Create a public GitHub repository, for example `adharsh-portfolio`.
2. Upload `index.html`, `styles.css`, `script.js`, and the `assets` folder to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then Save.
6. GitHub Pages publishes the site at `https://YOUR-USERNAME.github.io/adharsh-portfolio/`.

Upload ALL files together. An old `styles.css` next to a new `index.html` will look broken.

## Structure
- `index.html` — all content and section markup.
- `styles.css` — design tokens at the top, then header, hero, sections, responsive rules.
- `script.js` — mobile menu, scroll progress bar, section-aware navigation, reveal-on-scroll.
- `assets/adharsh-cutout.png` — transparent portrait used in the hero.
- `assets/adharsh-hero.png` — original portrait, kept for reference.

## Design notes (v8)
Full rewrite of the visual layer:
- Type pairing: **Inter Tight** for structure, **Instrument Serif** italic for the accent words, **JetBrains Mono** for labels.
- One accent colour (lime `#d8ff4d`) used sparingly, on a near-black warm-neutral base.
- Hero: editorial split with a large portrait stage, thin ring and ambient glow, plus a hairline facts row along the bottom.
- Fixed header with scroll progress, numbered nav and active-section tracking.
- Work cards use CSS-only artwork in place of images; a subtle reveal-on-scroll runs through the page and respects `prefers-reduced-motion`.
- Contact panel stays lime with WhatsApp, email and LinkedIn buttons.

## Before publishing
- Replace the generic LinkedIn homepage URL with your actual profile URL if it changes.
- Review the experience wording and dates for accuracy.
- No admissions performance numbers are included in this version.

The website links to `https://claryfi.in` and `https://entitlex.in`.
