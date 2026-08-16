# Table for N — codelab source (authoring)

The instruction manual + assets for the **Table for N** self-evolving-agent
lab. The runnable lab code lives separately at
[cuppibla/loop-lab-table](https://github.com/cuppibla/loop-lab-table) — this
repo is only the book.

- `CODELAB.md` — claat-format source (11 steps)
- `img/` — all figures: felt art, architecture SVGs (`img/src/`), terminal
  frames, adk-web / app / console screenshots
- `captures/` — raw terminal text the term-frames are rendered from

Build & serve locally:

```bash
claat export CODELAB.md && cd loop-lab-table && python3 -m http.server 9303
```

Migration target: `CloudVLab/gcp-devrel-content` → `labs/adk2004-self-evolve-agent`
(Qwiklabs format — see the migration plan in the vault).
