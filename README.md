<p align="right"><a href="README.pt-BR.md">🇧🇷 Português</a></p>

<p align="center"><a href="https://whatevertr.github.io/nud-jogo-taxonomia/"><img src="assets/banner.svg" alt="Constelação Taxonômica" width="100%"></a></p>

# Constelação Taxonômica

### ▶ [**Play in the browser →**](https://whatevertr.github.io/nud-jogo-taxonomia/)

A small browser puzzle game about **organizing context into taxonomies**. You drag concepts and connect them under the right group, building a classification tree. It is, basically, the [Constellation Method](https://github.com/whatevertr/nud-constellation-method) as a game: the skill of putting scattered information into the right structure, practiced level by level.

> **Status.** Work in progress. This is **Wave 1**: seven playable levels, from concrete taxonomies to epistemic distinctions. More levels (and a deeper engine) will come later, I have a day job and not much spare time.

## Play

**[Play now at whatevertr.github.io/nud-jogo-taxonomia](https://whatevertr.github.io/nud-jogo-taxonomia/)** — press **JOGAR**. No install, no server. (Prefer offline? Clone the repo and open `index.html` locally; it works with no server.)

- **Drag** a concept and **drop it onto** another to connect it.
- Drop on empty space to just **move**; **double click** to disconnect.
- **Hints** come from three characters (the Tríade), each in its own register, and **cost points**.
- **DESISTIR** (give up) solves the level but scores zero.
- Toggle **light / dark** any time.

**Score:** each level is worth 100, minus 20 per hint used, zero if you gave up.

## The levels (Wave 1)

From the concrete to the method:

1. Animals (a taxonomy tree)
2. Data types (number, text, date)
3. Analysis types
4. Fact vs opinion
5. The 5 whys (a causal chain)
6. Rule vs epistemic floor
7. Manual vs information

## Tech

- **Vanilla HTML5 Canvas.** No framework, no build step, no dependencies.
- **Single self-contained file** per page. Sprites are inlined; nothing is fetched at runtime.
- **Ordered dithering** (Bayer 4x4) for the background; solid pixel nodes on top.
- Boot-time assertions guard the core invariants. Respects `prefers-reduced-motion`. Two themes.

Built with AI assistance, using the Constellation Method to keep context coherent across many sessions.

## License

Two licenses (see [`LICENSE`](LICENSE)):

- **Code and content** (engine, puzzles, level text, docs): CC BY 4.0.
- **Brand assets** (the NUD identity, the Tríade characters, the marks): proprietary, all rights reserved, not licensed for reuse.

© 2026 Thainá Ramos (Nud by Whatevertr).
