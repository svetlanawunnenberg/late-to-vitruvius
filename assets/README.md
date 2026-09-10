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

## Sound

The hooves and the fallback lyre are synthesised in the browser — no files, no
licence, no weight. The three recordings are real, and they are cleared.

### The music, and its credit

| Slot | Work | Size |
|---|---|---|
| 1 | Corelli, Concerto grosso in D, Op. 6 No. 4 — Adagio, Allegro | 2.7 MB |
| 2 | Bach, Brandenburg Concerto No. 3 in G — Allegro | 4.3 MB |
| 3 | Vivaldi, L'estro armonico, Op. 3 No. 8 in A minor — Allegro | 2.7 MB |

All three are performed by the **Advent Chamber Orchestra** (Roxanna Pavel
Goldstein, Musical Director), from the Al Goldstein collection at ibiblio.org
via [Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Audio_files_of_classical_music_by_the_Advent_Chamber_Orchestra),
released under [CC BY-SA 2.0](https://creativecommons.org/licenses/by-sa/2.0/).

**That credit is the licence condition and must stay** — in the game's music
list, and here. It is the whole reason these can be published when the earlier
files could not.

Downloaded as Ogg Vorbis and converted to 112 kbps MP3, which halves the weight
and plays on older iPhones that Ogg does not reach.

### Why the first three files were replaced

The originally supplied recordings were a *Master and Commander* soundtrack rip,
a Japanese BGM-library file, and an I Musici performance on Philips. The
compositions were correctly chosen and are long out of copyright — Corelli died
in 1713 — but **a public-domain composition is not a public-domain recording**,
and a performance carries its own copyright for decades. Crediting a commercial
recording does not license it; credit satisfies a Creative Commons licence, and
does nothing for an all-rights-reserved one.

The pieces here are the same three choices, played by an orchestra that gave
its recordings away.
