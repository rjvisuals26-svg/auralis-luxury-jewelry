# Auralis — Luxury Jewelry Website

A static, responsive luxury jewelry landing page built with **plain HTML, CSS, and JavaScript**. No frameworks, no build step.

## Structure

```
jewelry-website/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    ├── images/
    │   ├── hero-jewelry.jpg
    │   ├── craftsmanship.jpg
    │   ├── product-ring.jpg
    │   ├── product-necklace.jpg
    │   ├── product-earrings.jpg
    │   ├── product-bracelet.jpg
    │   ├── product-set.jpg
    │   └── product-rings2.jpg
    └── icons/
        ├── cart.svg
        ├── heart.svg
        ├── search.svg
        └── menu.svg
```

## Run

Just open `index.html` in your browser, or serve the folder:

```bash
npx serve .
# or
python3 -m http.server 8000
```

## Sections

Hero · Collections · Best Sellers · Craftsmanship · New Arrivals (slider) · Why Us · Testimonials · Instagram · Newsletter · Footer.

## Color Palette

| Purpose | Color |
| --- | --- |
| Primary Background | `#FAF8F5` |
| Secondary Background | `#F1E8DE` |
| Dark Brown | `#3B2A22` |
| Chocolate Brown | `#5A4033` |
| Gold Accent | `#C8A165` |
| Text | `#1F1F1F` |
| Light Text | `#777777` |

## Fonts

- Headings: **Playfair Display** (Google Fonts)
- Body: **Poppins** (Google Fonts)

## Editing

- Product data lives at the top of `script.js` (`bestSellers`, `newArrivals`, `testimonials`).
- Colors and typography live in CSS variables at the top of `styles.css`.
- All content is in `index.html`.
