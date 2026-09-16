# Danny Automotive — Website

Static site for GitHub → Vercel deployment. No build step required.

## Deploy
1. Extract this ZIP.
2. Upload the contents to your GitHub repo (replace existing files).
3. Vercel redeploys automatically, or import fresh: Add New → Project → Framework preset "Other", leave Build Command and Output Directory blank.

## What changed from the previous version
- New logo: an inline brake-rotor + caliper mark (crisp at any size, no more blurry scaled image) paired with a real text wordmark, so it never looks stretched or misaligned again.
- New type system: Big Shoulders Display (headlines), Space Grotesk (body/UI), IBM Plex Mono (labels/data) — replaces Anton/Rajdhani.
- New visual concept: a "work order / dispatch" identity — the hero ticket card, job-code tags on service cards, and the coverage "manifest" all tie back to how an actual repair shop writes up a job, instead of a generic dark hero + badge template.
- Motion tightened throughout: hover/interaction transitions now run 140–220ms (previously 250–300ms+), with one orchestrated hero entrance instead of scattered fade-ins on every element.
- Business details, phone number, service area and copy are unchanged and accurate: 347-722-0062, all 5 NYC boroughs + NJ, brakes/rotors specialty plus diagnostics, maintenance and general repair.

## Files
- `index.html` / `styles.css` / `script.js` — the site
- `assets/mark.svg` — standalone favicon/social icon (the on-page logo is inline SVG in index.html so it can use the site's fonts and colors)

## Service request form
Serverless by design — it opens a pre-filled SMS to Danny Automotive. No backend needed.
