# Reference photos

- `minimi-right-side.jpg` — right side, long barrel and fixed butt. Supplied by the project owner, who confirmed on 2026-11-16 that it may be published. Source not recorded here.
- `minimi-para-left-side.jpg` — left side, Para variant. Supplied the same way; kept for reference, not used by the page.
- `minimi-right-side-texture.jpg` — the right-side photo levelled (8.53°), cropped, with the bipod legs and trigger blade cut out and edge colours bled outward. This is the texture the page embeds.
- `minimi-right-side-depth.png` — half-thickness map for the same crop (white = thickest, black = no body), estimated by region in `../source/build_relief.py`.

- `minimi-views-top.jpg` — F89 Minimi render by Stefan Yordanov for SimCentric (left, top and right views). Only measurements are used: the body half-widths in `../source/build_relief.py` (handguard and feed cover 5.0 cm across, receiver 4.7, butt 4.1, rail 2.1) and the pouch footprint. Not committed to the public repo (see `../.gitignore`), since no licence is recorded for it.

The ammo pouch is modelled from the owner's photos of the Auscam 200-round pouch (soft bag, hard black top with a sloped edge and a latch). Its camouflage is generated in code, not taken from the photos.

`../f89-assets.js` is the texture and depth map embedded as data URIs. Regenerate it from the project root with `python3 source/build_relief.py`.
