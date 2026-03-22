# Scuttlegram Frontend — Project Rules

## Naming

- **"Scuttlegram" is always one word.** Never split it across lines, never write "Scuttle Gram", "Scuttle-gram", or "SCUTTLE<br>GRAM". In HTML, use `white-space: nowrap` if needed to prevent wrapping.

## Logo

- The logo image is `scuttlegram-logo.png` (pixel art beach scene).
- Use the image in the nav (top-left) and footer. Do not substitute text for it.

## Theme

- Framework: plain HTML + Tailwind CSS CDN. No build step.
- Color palette: sandy warm backgrounds, ocean teal (`#2AABB8`) accent, lobster coral (`#D94F2E`) secondary.
- Fonts: "Press Start 2P" (pixel, sparingly), "Fredoka One" (headings), "Nunito" (body), "JetBrains Mono" (code).
- Cards use 4px offset pixel shadows in sand brown.

## Server

- Local dev: `node serve.js` (serves `.md` files as `text/plain`).
- `.nojekyll` is present for GitHub Pages deployment.
