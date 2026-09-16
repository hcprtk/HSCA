# HSCA practice icons

Six original SVG icons drawn to complement the bundled Flaticon outline style.
Each uses a 64 × 64 viewBox, 2-unit rounded strokes, transparent background,
and currentColor. These are new artwork, not additions to the Flaticon font.

Open preview.html for the gold-circle, black-outline, and hover previews.
The existing site displays its icons at 50px inside 130px gold circles.

For site integration, inline the SVG and set its width and height to 50px;
currentColor inherits the surrounding CSS color. Use unique title IDs when
repeating an icon. For decorative icons beside a heading, remove role/title/
aria-labelledby and add aria-hidden="true". An SVG loaded with an img tag
renders black by default and does not inherit the page color.

The six icons are also inlined as decorative SVGs in practice-areas.html.
Existing Flaticon font files are unchanged.
