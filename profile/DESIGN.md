# Organization profile design

Brand reference: https://www.deo-core.codes (reviewed 2026-11-14).
Palette: #171719, #f7f7f7, #1d1d1d, #F08331. Large editorial sans-serif headings and numbered sections adapt the site's visual language.

## GitHub compatibility

- Native Markdown for copy, headings, project links and contact information.
- GIF hero: 1280×620, 48 frames at 120 ms (5.76-second loop). Copy stays still; only the orange mark rotates. First frame is complete. Static PNG is linked alongside it.
- Static SVG panels use explicit dimensions and viewBox, local text and shapes. No JavaScript, foreignObject, remote fonts, embeds or CSS dependencies.
- Light panels stay light in both GitHub themes. The surrounding Markdown follows the reader's GitHub theme; GitHub does not support custom page CSS or arbitrary typography in README text.
- All images have descriptive alt text; all important project and contact links are native Markdown. Images scale within GitHub's content width.
- Asset URLs are pinned to the asset commit so previews work before merge and survive branch deletion. To update artwork, change the URL to the new asset commit.

## Content evidence

- https://www.deo-core.codes — studio description, services, process and public email.
- https://github.com/DEO-CORE/hackathon-arta/blob/main/README.md — ARTA purpose, components and local demo-data limitation.
- https://github.com/DEO-CORE/kisa_ecommerce/blob/main/README.md — KISA Ecommerce scope and technologies.
- https://github.com/DEO-CORE/termoclimat-kg — public description and TypeScript source.

No client counts, awards, revenue, usage statistics or unverified launch claims are included. Website concept mockups are not presented as shipped public products.
