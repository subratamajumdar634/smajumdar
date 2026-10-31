# Subrata Majumdar — Academic Website

Academic website of Subrata Majumdar, Postdoctoral Fellow at TIFR Centre for Applicable Mathematics, Bengaluru.

**Live website:** https://subratamajumdar634.github.io/smajumdar/

## Website features

- Responsive homepage, research, publications and preprints, academic profile, and contact
- Mobile navigation, light/dark mode
- Academic profile links to Google Scholar, ResearchGate, and MathSciNet
- Live visitor page-view counter powered by [Hits](https://hits.sh/)
- Optional direct contact form powered by Formspree; mailto fallback is enabled

The site is a custom static HTML/CSS/JavaScript implementation inspired by the visual style of al-folio. It is not a fork of the upstream Jekyll theme.

## Visitor counter (active automatically)

The footer includes one SVG badge loaded from:
`https://hits.sh/subratamajumdar634.github.io/smajumdar.svg?style=flat-square&label=page%20views&color=176b94`

Every ordinary page load causes a request for this badge. The counter begins when the updated site is deployed; it cannot recover visits from before that. It counts page views/hits (not deduplicated people); page refreshes or bots may contribute. To inspect statistics, open:
https://hits.sh/subratamajumdar634.github.io/smajumdar/

The count works **without an account, secret, or backend**. The Hits badge service says it does not use cookies or collect IP addresses or user agents: https://hits.sh/privacy/. The website sends a request to hits.sh when someone visits; this is a third-party service. If it is unavailable or blocked, the badge may not display, but the rest of the site still works.

## Activate direct contact-form submissions (optional)

1. Create a form at https://formspree.io/ directed to your preferred inbox.
2. Set `formspreeFormId` in `config.js` using the final URL segment from `https://formspree.io/f/FORM_ID`.
3. Test a submission on the published site.

Without a Formspree ID, submitting the form opens the visitor's email app with a prepared message.

## Maintaining the site

- Edit `index.html` to update profile details and the `preprints` / `publications` arrays.
- Edit `config.js` only for optional Formspree setup.
- Add a portrait, full CV PDF, and direct DOI/arXiv/PDF links when available.
- Never store passwords or private access tokens in this public repository.

## Hosting

GitHub Pages is configured to deploy from branch `main` at repository root.
