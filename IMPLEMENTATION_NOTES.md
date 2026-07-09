# Implementation Notes

- The eight reference JPEG files were moved into `references/` before implementation.
- This mock is plain HTML/CSS/JavaScript and can be opened directly from `index.html`.
- Reference images are used as cropped visual assets inside sections, not as a single full-page background.
- Colors, spacing, and typography are centralized in `css/tokens.css` for future iteration against screenshots.

## 2026-07-09 PC visual iteration notes

- Improved the 1440px-oriented layout to better follow the reference sequence: larger dark hero, two-row photo mosaic, expanded story block, dark solution cards, alternating values, horizontal case studies, Stories, Insights, FAQ, CTA, and footer.
- The current mock still reuses the eight full reference JPEGs as cropped section imagery. Original separated photographs, device screens, product shots, plant line art, paper textures, and dashboard/report assets are still required for closer reproduction.
- Hero uses `reference-01.jpeg` as a temporary background per the spec allowance, with HTML text and CSS device mock layered above it. This may still show reference-image text/artifacts depending on crop and viewport.
- Wave boundaries are CSS approximations and should be replaced with more precise SVG curves after visual approval.
- Further screenshot comparison at 1440px should focus on: hero crop/device placement, photo mosaic crop positions, Solutions 03/04 visual density, detailed Cases thumbnail structure, and the missing fine botanical/particle decorations.
