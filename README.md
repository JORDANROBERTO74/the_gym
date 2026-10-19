# THE GYM — Landing Page

Landing page for a (fictional) premium gym. A frontend showcase built with **vanilla HTML, CSS and JavaScript** — no frameworks, no build step.

## Highlights

- **Dark, athletic design system**: volt accent, condensed display type (Anton) + Inter.
- **Responsive**: 320px → 1440px, mobile-first.
- **Accessible**: skip link, semantic landmarks, keyboard navigation, visible focus, labeled form fields, `prefers-reduced-motion`.
- **Interactive**: accessible mobile menu, scroll reveal, gallery lightbox (`<dialog>`), contact form validation.
- **Performance**: all images in WebP (~9 MB → ~1 MB), no icon fonts (inline SVG).
- **SEO**: meta description, Open Graph/Twitter, JSON-LD `HealthClub`, favicon.

## Sections

Hero · Marquee · Programs · About · Amenities · Trainers · Gallery · Pricing · Testimonials · CTA · Contact · Footer.

## Stack

- HTML5
- CSS3 (custom properties, Grid, `clamp()`)
- Vanilla JS (`IntersectionObserver`, `<dialog>`)

## Structure

```
index.html
styles.css
main.js
favicon.svg
.nojekyll
img/
  fondo.webp
  fondo-servicios.webp
  fondo-galeria.webp
  nosotros.webp
  servicios.webp
  e1.webp · e2.webp · e3.webp
  f1.webp … f6.webp
```

## Run locally

Open `index.html` directly, or serve the folder:

```bash
python -m http.server 8080
```

Then visit <http://localhost:8080>.

## Live preview

<https://jordanroberto74.github.io/the_gym/>

## Notes

- **Demo / fictional content**: gym name, address, prices, trainers and testimonials are illustrative.
- The contact form is **front-end only**: it validates fields and shows a success state; no backend.

## Contact

[jordanroberto74@gmail.com](mailto:jordanroberto74@gmail.com)
