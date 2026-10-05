# S03E01 visual evidence manifest

**Knowledge boundary:** `S03E01`

Binary assets са качени в `main` преди този text-only analysis PR.

## Правила за обработка

- perspective correction на photographed TV plane;
- output normalized до `1536×864`;
- JPEG quality 95;
- no generative editing;
- no content reconstruction, object removal или synthetic fill;
- subtitles, glare/reflections и visible scene content са запазени;
- no external/future-episode sources.

## Selected frames

| File | Evidence / context | Git blob SHA |
|---|---|---|
| `screenshots/level-1-juliette-opening.jpeg` | E437–E441 — Juliette opening / Level 1 context. | `d32271dd2734b76d79e695487c8f1f36b45de595` |
| `screenshots/daniel-keen-name-reveal.jpeg` | E443 — Congressman identified as Daniel Keen. | `c3a81df8ec48c8e7225ea15e78750270e0f0e7ee` |
| `screenshots/juliette-surveillance-feed.jpeg` | E444 — Juliette under surveillance. | `ecff9315065da5ecc155d11881ef186ecdc2d019` |
| `screenshots/sims-surveillance-control-room.jpeg` | E447 — Sims / central surveillance room context. | `8f0ecdc4de91e2a270be600691d05c6d75770894` |
| `screenshots/juliette-three-minute-airlock.jpeg` | E448 — stated three-minute chamber duration. | `796d7f7436ad469c7931b4d41f23e83b0d5f12ee` |
| `screenshots/level-67-bernard-furnace-transport.jpeg` | E453–E454 — Level 67 + Bernard transport to furnaces. | `0e4a298bf1f6b054e483856f27aa34281fcb85b0` |
| `screenshots/level-87.jpeg` | E482 — Level 87. | `97fdee2af74f8bbb319f09dd8f10677d88353eb3` |
| `screenshots/display-is-lie-mural.jpeg` | E483–E484 — persistent anti-display/truth movement. | `523c541c644ff67bf1ef29f0ad2a1ba42e9cb906` |
| `screenshots/computer-this-concerns-me.jpeg` | E498–E500 — computer/system concern over memory recovery. | `9a8b349eb8bca3b7c363fcfdf48f5363aa9b4cd4` |
| `screenshots/note-want-to-know-the-truth.jpeg` | E509–E510 — opening note text / bowl instruction context. | `4d375b9963a08f46d73153c814cf974befc0e2d0` |
| `screenshots/note-level-2-marketplace-burn-this.jpeg` | E512–E515 — marketplace on Level 2 + `BURN THIS`. | `df515d44437e775b2096a8660b6a39ea47b46324` |

Contact sheet Git blob SHA: `08c5966facec9fde4cf5218de8f7eb6ab561b8d9`.

## Validation

Всички 11 screenshots + contact sheet са валидирани byte-for-byte чрез Git blob SHA comparison срещу локално подготвения package преди analysis PR-а.

`contact-sheet.jpg` е auxiliary/navigation asset, не primary evidence.