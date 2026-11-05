# Adharsh M. — Personal Portfolio

A responsive, dark-theme personal portfolio built with plain HTML, CSS and JavaScript.

## Preview locally
Open `index.html` in a browser.

## Publish free with GitHub Pages
1. Create a public GitHub repository, for example `adharsh-portfolio`.
2. Upload `index.html`, `styles.css`, `script.js`, and the `assets` folder (including `adharsh-hero.png`) to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then Save.
6. GitHub Pages will publish the site at `https://YOUR-USERNAME.github.io/adharsh-portfolio/`.

## Before publishing
- Replace the generic LinkedIn homepage URL with your actual LinkedIn profile URL.
- Add a professional email address or preferred contact link.
- Add a profile photo if you want one.
- Review the experience wording and dates for accuracy.
- The website links to `https://claryfi.in` and `https://entitlex.in`.

No build tools or paid hosting are required.


The hero portrait is included in `assets/adharsh-hero.png`. This version intentionally omits admissions performance numbers until you approve them.

## Version 3 hero update
The hero portrait is integrated into the page background with a soft fade, and the hero order adapts for desktop and mobile. On mobile the headline comes first, then the portrait, then supporting copy and actions. No admissions performance numbers are included.

## Version 4 — Overflow Hero
The hero portrait now uses a transparent PNG cutout layered directly on the charcoal page background. A lime orbital ring and ambient glow sit behind the subject. The portrait overhangs the hero area on desktop and scales/centres on mobile. No admissions numbers have been added.

## Version 5 — Mobile hero refinement
Tightened the mobile hero by reducing the portrait stage height and image scale, slightly reducing headline size, refining the orbital ring and reducing spacing. Desktop layout remains unchanged. No admissions numbers included.


V6: Reference-matched hero with bright lime arc, border, bottom glow, portrait overflow, desktop split and mobile stacked layout. No admissions metrics added.

## Version 7 — Overflow Hero rebuild
Replaced the stacked V3–V6.1 hero CSS with one clean block at the end of `styles.css`.
- Desktop: rounded hero card; the portrait is cropped by the card's bottom edge and its head rises past the glowing lime ring.
- Mobile: headline, then portrait inside the ring, then intro text and buttons. Nothing overlaps the text.
- Ring and portrait are sized from their own stage (container units), so they stay in proportion at every width.
- Fixed the sideways scroll on tablet and small laptop widths.
- The navigation now lines up with the hero card's inner edges.
- Removed the unused `hero-reference.css` (it was never linked from `index.html`).
- Contact section: WhatsApp (prefilled message), email and LinkedIn are full buttons. No email or number is shown as text.
- V7.1: thicker ring with a stronger glow, larger portrait and better placement on mobile, fixed a see-through watch face in the cutout, and added `?v=7.1` to the CSS/JS links so phones reload the new files.
- When publishing, upload ALL files (index.html, styles.css, script.js and the assets folder). An old styles.css next to the new index.html makes the page look broken.
