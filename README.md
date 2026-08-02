# patchthrough-site

The landing page for [Patchthrough](https://github.com/nico-herrera/patchthrough).

One static `index.html` — inline CSS, inline SVG, no build step, no
dependencies. Visual tokens come from the app's `Sources/patchthrough/UI/Theme.swift`;
copy follows `design/DESIGN_RULES.md` (sentence case, "Patch through to", red
only on the record dot and primary action).

The macOS app and npm CLI are separate downloads. Keep the GitHub Releases app
as the primary call to action; npm installs only the standalone transcript
client and must never be described as an app installer.

## Deploy

Push this folder to its own repo and enable GitHub Pages on the default branch,
or drop it on Netlify/Vercel as a zero-config static site. To work on it
locally, just open `index.html` in a browser.
