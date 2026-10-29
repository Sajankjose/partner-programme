# Geojit Franchise Partner Website (HTML prototype)

This is a multi-page, responsive static website prepared from **Franchisee Brochure PDF.pdf** (28 pages) and Geojit Omnichannel Brand & Experience Manual v1.1. No CMS, framework or build process is required.

## Preview
Open `index.html` in your browser; navigation, chart switching, responsive layouts and accordions work offline. The official **Radio Canada Big** typeface loads through Google Fonts if connected to the internet; local fallback is provided. No font files are redistributed.

## Files
- `index.html` – landing page and conversion journey
- `why-geojit.html` – company, leadership, growth, recognition
- `advantages.html` – training, advisory, marketing, CRM, RMS and SPARC
- `products.html` – product range, Flip, FundsGenie, Smartfolios, research, NRI, PMS, AIF, Private Wealth
- `impact.html` – network and CSR
- `partner.html` – partnership enquiry form
- `thank-you.html` – redirect after Netlify Forms submission
- `legal.html` – statutory information
- `styles.css`, `script.js`, `assets/` – shared styling, interactions and brochure imagery
- `robots.txt`, `sitemap.xml` – **prototype placeholders**; update the domain and indexing rules before public launch.

## Form setup
`partner.html` is prepared for **Netlify Forms** (`data-netlify=true`, honeypot). It needs no CMS; deploy the entire folder to Netlify and verify that Netlify identifies the form in Forms dashboard. Configure notification recipients, privacy policy, data retention and client consent wording with stakeholders. The form does not submit from `file://` local preview. Official existing partner enquiry: https://partner.geojit.com/

## Publication review – mandatory
1. **PMS brochure page 18 contains internal editorial placeholder** (portfolio name/description mismatch). These disputed portfolio lists were intentionally omitted from the public-facing prototype. Research/Compliance to verify.
2. **Page 27 regional office breakdown adds to 521, not headline 529.** The site uses the brochure's company-wide figure 529 as at 30 Sep 2026 but does not present the conflicting breakdown.
3. The brochure does **not specify** franchise fee, investment requirement, revenue sharing or full application steps. Do not invent them; add when Business approves.
4. Review AIF/PMS/Smartfolios claims, 'research recommendations' wording, detailed regulatory registration numbers and relevant risk disclosures before go-live.
5. Validate management job titles and data dates; figures displayed remain as at 30 September 2026.
6. `sitemap.xml` includes a **placeholder domain** and `robots.txt` prevents indexing. Update both once the official deployment URL is known and Compliance approves.
7. Header logo was isolated from the user-provided PDF. All photographic imagery was extracted from the brochure; rights were presumed only for this prototype. Obtain confirmation for public usage.
8. Visual values follow the supplied Geojit Omnichannel Manual, but the production team should reconcile actual Figma tokens/component variants before publishing.
9. Form privacy consent needs appropriate approved privacy-policy link (an approved privacy notice link must be supplied). Fix before launch.

## Design system reference
Uses Radio Canada Big, primary #09877B and deep brand #032F2D / text #022F2D through semantic CSS aliases. Responsive navigation, accessible focus styles, restrained elevation, compact CTAs and brochure-style photography.

## Deployment
For Netlify: drag the **contents** of the site directory into Netlify Drop or connect the directory as the publish folder. `index.html` is at the root. There are no Node/npm dependencies.

## Content fidelity
Brochure content is condensed for scanning on the landing page and distributed across detailed pages. Secondary content uses source descriptions with some editorial tightening. Statutory text and claims require Compliance verification.
