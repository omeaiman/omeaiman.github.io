# Ome Aiman Rasheed: portfolio site

A one-page portfolio for Ome Aiman Rasheed, Digital Growth Manager and AI Automation Engineer. It shows dated results for two US technology companies (an AI sales platform and a software company) from Google Search Console, GA4, Semrush and Lighthouse readings, with a Then vs Now comparison, trend charts, case studies, career timeline, skills and contact. Company names are withheld at their request.

Plain HTML, CSS and JavaScript in one file. No build step, no framework, no chart library, no cookies and no trackers. The only outside request is the Inter font from Google Fonts.

Interactive parts, all in the same file: headline numbers count up when they scroll into view (skipped for visitors who prefer reduced motion); the trend charts switch between Weekly, Monthly and Since start views, with a tooltip on every bar and point; a light and dark theme toggle that follows the system setting until a visitor picks one (remembered in the browser); and a sticky "Hire me, book a free website review" button that opens a prefilled email.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole site: content, styles, chart code and chart data |
| `Ome-Aiman-Rasheed-Resume.pdf` | Resume, linked from the Resume and Download buttons |
| `og-image.png` | 1200 x 630 preview image for link previews |
| `favicon.svg` | Browser tab icon |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publish

Upload all files to a public repository named `<username>.github.io`, then turn on Settings, Pages, deploy from branch `main`, folder `/ (root)`. Replace the placeholder address `https://omeaiman.github.io/` in `index.html` (the `og:url`, canonical and two image tags) with your real one.

## Updating the numbers

Every number is typed in by hand from a dated report. Update both places:

1. The static text and tables in `index.html` (stat cards, Then vs Now tables, case studies).
2. The chart data at the top of the `<script>` block: `WEEKLY`, `TRACKER`, `MONTHLY`, `SINCE` (baseline vs now, copied from the Then vs Now tables) and `SPEED`.
