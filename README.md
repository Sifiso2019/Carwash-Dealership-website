# Sifiso Dealership Website

A single-page, dark-themed website for **Sifiso Dealership**, a car dealership based in Protea Glen, Soweto. Built as a static HTML/CSS/JS page — no build step or framework required.

## Features

- Responsive hero section with headline, CTA buttons, and stats bar
- Vehicle inventory grid with filter tabs (New / Used / etc.)
- "Why Choose Us" section highlighting inspections, financing, trade-ins, and warranty
- Finance promo band with pre-approval CTA
- Customer testimonials
- Contact section with business details and an enquiry form
- Fully responsive layout (mobile breakpoint at 900px)

## Tech Stack

- **HTML5** — single-file structure
- **CSS3** — custom properties (CSS variables), CSS Grid/Flexbox, no external framework
- **Vanilla JavaScript** — small script for inventory filter tab interaction
- **Google Fonts** — Barlow & Barlow Condensed

## File Structure

```
.
└── index.html   # entire site: markup, styles, and script in one file
```

## Getting Started

No installation needed — it's a static HTML file.

1. Clone the repo
   ```bash
   git clone <your-repo-url>
   cd sifiso-dealership
   ```
2. Open `index.html` directly in a browser, or serve it locally:
   ```bash
   npx serve .
   ```

## Customization

- **Colors & fonts**: edit the CSS custom properties at the top of the `<style>` block (`--red`, `--black`, `--display`, `--body`, etc.)
- **Inventory**: update the car cards inside the `.cars-grid` section (make, model, price, badge, specs)
- **Contact details**: update address, phone, WhatsApp, and email inside the `#contact` section
- **Testimonials**: edit the cards inside `.testi-grid`

## Notes

- The contact form is front-end only — connect it to a backend or a form service (e.g. Formspree, Netlify Forms) to actually receive enquiries.
- Placeholder social links (`#`) in the footer should be updated with real profile URLs.

## License

© 2025 Sifiso Dealership. All rights reserved.
