# llm-kit-site

Landing page for The Self-Hosted LLM Kit, served at https://kit.djeango.com

One static page, no build step. `index.html` contains everything: styles, the
embedded Fit Check tool, the email capture wired to Kit, and the share block.

## Editing

Source of truth is on the Djeango workstation at
`Desktop/LLM KIT - MASTER/5 - Sales and Listing/`.
Edit there, then upload the file here as `index.html`.

## URLs baked into the page

Three references point at https://kit.djeango.com (canonical, Open Graph image,
and the share links). If the domain moves, change all three.

## Email capture

Posts to Kit form 9689272. Falls back to the hosted Kit form at
https://djeango-tech.kit.com/4d20c4bd34 if the browser blocks the cross origin
request.

## Files

| File | What it is |
|---|---|
| index.html | The whole page |
| og-llm-kit.png | 1200x630 social share card |
| CNAME | Tells GitHub Pages to serve kit.djeango.com |
| .nojekyll | Stops Jekyll processing, we serve raw HTML |
