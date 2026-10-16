# Total Halo — mobile flow prototype

Clickable iOS wireframe of the Total Halo scam-check flow: day-0 onboarding,
screenshot capture, the narrated check, and the verdict with its clarification
turns.

**Live:** https://wenyu-pango.github.io/total-halo-flow/

This is a **Gate 1 wireframe** — deliberately unstyled. Grey boxes, no colour,
no icons, real copy. It exists to settle flow and screen order before any
styling is built.

Nothing here is connected to a real scam engine; every verdict is written copy
standing in for one.

## Source

`index.html` is **generated**. The source of truth is `prototype.html` in the
Total Halo working folder, built by `build-artifact.py`, which emits two targets:

- `dist/total-halo-flow.html` — for claude.ai Artifacts (no document skeleton;
  the platform supplies one)
- `dist/public/index.html` — this file (standalone, for static hosting)

Edit the prototype, re-run the build, copy `dist/public/index.html` here, push.
