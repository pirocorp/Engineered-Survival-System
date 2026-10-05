# S03E05 visual evidence manifest

**Knowledge boundary:** `S03E05`

Binary assets са качени в `main` преди този text-only analysis PR.

## Правила за обработка

- perspective correction на заснетия TV plane;
- output normalized до `1536×864`;
- JPEG quality 95;
- без generative editing;
- без content reconstruction, премахване на objects или synthetic fill;
- visible scene content е запазено;
- без external/future-episode sources.

## Selected frames

| File | Evidence / context | Git blob SHA |
|---|---|---|
| `screenshots/level-95.jpeg` | E753–E754 — Level 95 direct spatial anchor / active stairwell-transit context. | `6e01e61f22b0484f5a15c1d6c55ab1146a4535c2` |
| `screenshots/riser-installation-construction-board.jpeg` | E758–E759 — `FRAME ASSEMBLY + RISER INSTALLATION` construction-stage board; welding/alignment/tread/cross-brace workflow. | `e9d2e25de9cc10c3bd712487f244dd0e6b27b6ee` |

Git blob SHA на contact sheet: `fc6e2841d6cffa1be144eb0954482275a6dedfff`.

## Validation

Всички **2 screenshots + contact sheet** са валидирани byte-for-byte чрез Git blob SHA comparison спрямо локално подготвения package преди analysis PR-а.

`contact-sheet.jpg` е auxiliary/navigation asset, а не primary evidence.
