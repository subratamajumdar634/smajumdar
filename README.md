# Subrata Majumdar — Academic Website

This repository hosts the academic website of Subrata Majumdar, Postdoctoral Fellow at TIFR Centre for Applicable Mathematics, Bengaluru.

**Website (after GitHub Pages is enabled):** https://subratamajumdar634.github.io/smajumdar/

## Website

- Responsive homepage, research, selected publications, academic career, and contact pages
- Mobile navigation, light and dark modes
- Links to Google Scholar, ResearchGate, MathSciNet, and GitHub
- Optional GoatCounter visit analytics and optional Formspree direct contact form

The website is a lightweight custom HTML/CSS/JavaScript implementation **inspired by al-folio's visual style**. It is not the upstream al-folio Jekyll theme.

## Enable GitHub Pages

Go to **Settings → Pages → Build and deployment**, select **Deploy from a branch**, choose branch **main** and folder **/(root)**, then save.

Your site URL will be https://subratamajumdar634.github.io/smajumdar/.

## Activate visitor analytics

1. Register a site at https://www.goatcounter.com/ for the website URL above.
2. Edit `config.js`: set `goatcounterCode` to the site subdomain in your `*.goatcounter.com` dashboard URL.
3. In GoatCounter settings, allow a public visitor counter if you want the numbers shown on your website.
4. Visit the Analytics tab and your GoatCounter dashboard to verify counting.

Before activation, counts intentionally show —, not fabricated numbers.

## Activate direct contact form submissions

1. Create a form at https://formspree.io/, directed to your preferred inbox.
2. Edit `config.js`: set `formspreeFormId` to the ID from https://formspree.io/f/FORM_ID.
3. Test a form submission.

Without Formspree configuration, the contact form opens the visitor's email app with a prepared message. This fallback needs the visitor's own email app.

## Maintenance

- Edit `index.html` to update information and the `papers` array.
- Edit `config.js` to enable third-party services.
- Add a photograph, complete CV PDF, and direct DOI/arXiv/PDF links as available.
- Do not add passwords, tokens, or private keys to the public repository.

## Local preview

Open `index.html` directly, or run `python3 -m http.server 8000` in the repository directory.
