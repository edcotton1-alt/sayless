# Say Less. Mean Everything.

A scroll through the craft of compression. From the Globe to the group chat.

## Files

- `index.html` — the whole site, single file
- `og-image.png` — Open Graph share card (1200×630)
- `og-image.svg` — source for the share card

## Deployment

Deployed on Vercel. The HTML is a single self-contained file with inline CSS and JS. No build step. Just serve the directory.

## Edit

To change the share card image, edit `og-image.svg` and re-export to PNG at 1200×630.

To change the metadata sentence (appears in link previews), edit the `<meta name="description">` and matching Open Graph and Twitter card tags in `index.html` head.

To change the canonical URL (after setting up a custom domain), find and replace `say-less.vercel.app` in `index.html`.
