# Meridian Website — Hypersphere Style Rebuild

## Task
Build a single-page static HTML website for Meridian (meridianrwa.com) that clones the visual aesthetic of hypersphere.capital. The site should be clean static HTML/CSS/JS — no frameworks, no build step.

## Design Reference
- `hypersphere-design-reference.html` — the full Hypersphere homepage HTML
- `hypersphere-reference.css` — the full Hypersphere CSS (includes Tailwind utilities + custom styles)
- `ref-fonts/` — Unica 77 font files (woff2)

## Key Design Elements to Replicate
1. **Color scheme**: Change from Hypersphere blue (#0501f9) to a deep navy/dark tone suitable for financial infrastructure
2. **Typography**: Use the Unica 77 fonts from ref-fonts/ (or Inter as fallback)
3. **Layout**: Clean grid system, generous whitespace, editorial feel
4. **Navigation**: Fixed top nav with pill-style links, logo on left
5. **Hero section**: Full-viewport hero with background visual + tagline
6. **Smooth animations**: Fade-in on scroll, text slide-up animations (CSS-only or minimal JS)
7. **Footer**: Multi-column links, socials, clean dividers
8. **Mobile responsive**: Must work on mobile

## Meridian Content
Use content from `meridian-content-reference.html` as the source for Meridian's actual text/copy. Key sections:
- **Hero**: "Meridian — Tokenization infrastructure for real-world assets"  
- **Thesis**: Why tokenization matters (from the existing site)
- **Infrastructure**: What Meridian builds (token issuance, custody, compliance)
- **Contact**: contact@meridianrwa.com

## Assets
- `meridian-logo.svg` and `meridian-logo.png` — use these for the logo
- `favicon-16.png`, `favicon-32.png`, `apple-touch-icon.png` — favicons

## Background Graphic
Instead of Hypersphere's blue abstract blob, create a subtle dark geometric/grid pattern using CSS (no external images needed). Think: subtle grid lines or a topographic map pattern. Something that says "infrastructure" not "crypto fund."

## DO NOT
- Use gold (#c9a227) anywhere
- Use "Forma Capital" anywhere — the parent company is "SMG"
- Make it look like a SaaS product page
- Include any Hypersphere branding or content

## Output
Create `index.html` as the main file. Put fonts in `fonts/`, CSS can be inline or in a separate file. Keep it simple — one HTML file is ideal.

## Footer
Should say: "© 2026 Meridian" and link to SMG: <a href="https://smgholdings.com">SMG</a>
