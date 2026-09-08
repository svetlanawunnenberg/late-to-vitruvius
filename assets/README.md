# The artwork

These are Svetlana's drawings, cropped out of the 1678×937 canvas they were
generated on and scaled for the web. **The originals live in
`Downloads\Late to Vitruvius\` — keep them.** Everything here is derived and
can be rebuilt from them.

## What the game uses

| File | Made from | Used for |
|---|---|---|
| `pomegranate.png` | `Pomegranate_.png` | the fruit, whole |
| `pomegranate-split.png` | `Pomegranate Splatted.png` | the fruit the instant it opens |
| `scroll.png` | `Scroll unrolled_.png` | the parchment behind a question |
| `chariot-biga.png` | `2 horse carraige (1)_.png` | the two-horse chariot |
| `chariot-quadriga.png` | `4 horse carraige (1)_.png` | the four-horse chariot |
| `chariot-carpentum.png` | `4 horse carraige fancy (1).png` | the fancy four-horse chariot |
| `button.png` | `button design.png` | not wired up yet |
| `leg1-a.jpg` / `leg1-b.jpg` | `Approaching Rome pt 1` / `pt 2` | leg I, far plate then near plate |
| `leg2-a.jpg` / `leg2-b.jpg` | `The Aqua Claudia pt 1` / `pt 2` | leg II |
| `leg3-a.jpg` / `leg3-b.jpg` | `Vicus Romanus pt 1` / `pt 2` | leg III |
| `menu.jpg` | `MENU BAR of three locations.png` | not wired up yet |

## Two things worth understanding

**The `pt 1` / `pt 2` pairs are a dolly.** Each pair is the same view at two
distances, near and far. The game cross-fades and scales from `-a` to `-b` as
you cover the eight modules of a leg, so finishing a leg *is* arriving. That is
what makes the road feel like a road without a single line of paving being drawn.

**The "with shadow" versions are not used, on purpose.** Those have a shadow
baked into the image, so it is fixed. The game casts its own shadow instead —
the same artwork struck in black, offset beneath the piece, with its weight and
throw driven by how the run is going. That is the effect that was asked for, and
a baked shadow cannot do it. The plain versions are the right source.

## Rebuilding

The two scripts that made these files crop to the alpha bounding box and resize.
They are throwaway, but the recipe is: find the content bounds, add ~2% padding,
scale so the longest side is the target, save PNG for anything with
transparency and JPEG for the opaque backdrops. `System.Drawing` from PowerShell
does all of it — no Photoshop needed.

## If you redraw anything

- **Transparent PNG** for objects, and the ink can be tonal — the chariots are
  full engravings with both dark and light areas, and that works.
- **Chariots must be from behind**, at the same eye level as each other. The
  whole camera depends on it.
- Keep an object under about 300 KB and a backdrop under about 400 KB.
- Nothing from the office archive, ever. This repository is public.
