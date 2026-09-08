# Late to Vitruvius

**A racing game about the vocabulary of classical architecture.**

Vitruvius is teaching this morning and you are on the wrong side of Rome. Take a
chariot, split pomegranates for time, and read every scroll the road throws at you —
because he will not seat a student who has not studied.

Three legs, eight scrolls each, seventy-odd terms drawn from *De architectura*
and the Renaissance treatises that codified it. At the door you are graded on
**firmitas**, **utilitas** and **venustas**.

**▶ Play it: <https://svetlanawunnenberg.github.io/late-to-vitruvius/>**

---

## What is in it

| Leg | Ground | What it drills |
|---|---|---|
| I | The Forum | The parts of a building, plainly named — column, cornice, portico, quoin |
| II | The Via Appia | The grammar of the orders — triglyph, entasis, cyma reversa, modillion |
| III | The Steps of the Basilica | Vitruvius himself — the five intercolumniations, the six principles, the temple plans |

Every term is also listed in **the Scriptorium**, a plain glossary page inside
the game, with each entry marked as either Vitruvian or a later codification.

Two answer modes. **Type the term** gives you a definition and you name it;
**Tap the meaning** gives you a term and three definitions. Typing is default on
a keyboard, tapping on a phone. Spelling is forgiving — case, apostrophes,
hyphens and accents are all ignored, and a near miss gets a free retry.

Three chariots, each a genuinely different race:

- **Biga** — least time in the clock, fast ground, no forgiveness.
- **Quadriga** — most time, most value from fruit. Start here.
- **Carpentum** — the scholar's cart. Slow, but knowing the answer moves it a very long way.

## Running it

It is one HTML file with no build step, no dependencies and no server.
Double-click `index.html` and it runs. It works offline once the fonts have
loaded, on any modern browser, on Mac, Windows, iPhone and iPad.

## Illustrations

The game ships with hand-drawn SVG line art. Drop PNG files with these exact
names into `assets/` and they replace the drawings automatically — no code
change, and any file you leave out keeps its drawing.

```
assets/chariot-biga.png        ~800×500   side view, facing right
assets/chariot-quadriga.png    ~800×500
assets/chariot-carpentum.png   ~800×500
assets/pomegranate.png         ~256×256
assets/scroll.png              ~1200×800
assets/vitruvius.png           ~600×800
assets/road.png                ~2400×600  tileable left-to-right
```

All transparent PNG. Line engraving suits the design best.

## A note on accuracy

This is aimed at people who know the subject, so the term bank is the part that
matters. Definitions are kept to one sentence and each is marked in the
Scriptorium as either appearing in *De architectura* or belonging to the later
Renaissance codification — the Composite order, for instance, is **not**
Vitruvian, and the game asks about that on purpose.

Corrections to any definition are welcome and will be taken seriously. Open an
issue.

## Sources

- Vitruvius, *De architectura*, Books III–IV (Morgan translation, 1914, public domain)
- Vignola, *Regola delli cinque ordini d'architettura*, 1562
- Standard architectural glossaries for the post-antique terms

## Licence

MIT — see [LICENSE](LICENSE). Use it, fork it, teach with it.
