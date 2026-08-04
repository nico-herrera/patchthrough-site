# patchthrough-site

The landing page for [Patchthrough](https://github.com/nico-herrera/patchthrough).

The site is one static `index.html` with inline CSS and inline SVG. It has no
build step and no dependencies. Visual tokens come from the app's
`Sources/patchthrough/UI/Theme.swift`. The copy follows `design/DESIGN_RULES.md`:
sentence case, "Patch through to", and red only on the record dot and the
primary action.

The macOS app and the npm CLI are separate downloads. Keep the GitHub Releases
app as the primary call to action. The npm package installs only the standalone
transcript client. Never describe the npm package as an app installer.

Platform copy has one release boundary: the macOS app and cross-platform CLI are
available now; the Windows recorder is a hardware-validation preview. Link to its
public progress and acceptance checklist, but do not add a Windows download until
the repository publishes a tested installer.

## Deploy

Push this folder to its own repository and enable GitHub Pages on the default
branch. You can also drop the folder on Netlify or Vercel as a zero-config
static site. To work on the page locally, open `index.html` in a browser.
