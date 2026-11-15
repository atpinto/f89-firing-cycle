# Reference photos

- `minimi-right-side.jpg` — right side, long barrel and fixed butt. Supplied by the project owner, who confirmed on 2026-11-16 that it may be published. Source not recorded here.
- `minimi-para-left-side.jpg` — left side, Para variant. Supplied the same way; kept for reference, not used by the page.
- `minimi-right-side-texture.jpg` — the right-side photo levelled (8.53°), cropped, with the bipod legs and trigger blade cut out and edge colours bled outward. This is the texture the page embeds.
- `minimi-right-side-depth.png` — half-thickness map for the same crop (white = thickest, black = no body), estimated by region in `../source/build_relief.py`.

`../f89-assets.js` is the texture and depth map embedded as data URIs. Regenerate it from the project root with `python3 source/build_relief.py`.
