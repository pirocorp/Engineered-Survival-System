# S03E02 visual evidence manifest

**Knowledge boundary:** `S03E02`

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
| `screenshots/computer-note-deception-concern.jpeg` | E516–E519 — system awareness of note/deception and risk evaluation. | `a14206389209982e74458156fdf5387e1a43948e` |
| `screenshots/presilo-selective-memory-restore-omit.jpeg` | E524 — selective restoration/omission of memories. | `54fea7e7b326af4b9ee7d222e011595831957b00` |
| `screenshots/presilo-repeat-personal-history.jpeg` | E525–E526 — repeated autobiographical narrative as treatment component. | `4e1a228d8d1b6ef812c2d1ef832835b924a00a02` |
| `screenshots/presilo-can-suggest-a-lie.jpeg` | E528–E530 — false autobiographical narrative can be suggested/implanted. | `57183562c4cd48adcb64b1e564034c88d519d10e` |
| `screenshots/presilo-false-memory-takes-time.jpeg` | E531 — false replacement narrative takes substantial time/effort. | `31316fd978102fda3f275134006457ef166b2a8d` |
| `screenshots/presilo-real-memories-return.jpeg` | E532–E534 — real memories remain present and can return quickly. | `be849982240dc30d8e5e245ed3039395875f509b` |
| `screenshots/note-2-silo-council-cafeteria.jpeg` | E535–E536 — second covert note / Silo Council cafeteria instruction. | `bbd2bdd64bd825bbe850d4bf2268dfa5ec3f13a4` |
| `screenshots/note-3-partial-a.jpeg` | E537–E539 — third note, partially readable only. | `2f9b18e74bd9ac37689832071ac76e9fabadd214` |
| `screenshots/note-3-partial-b.jpeg` | E537–E539 — alternate third-note frame; transcription remains unresolved. | `122834fff519b83a815ebfc78fc7b2a868cce28e` |
| `screenshots/ai-risk-red-line.jpeg` | E540 — red risk line for Juliette. | `b818c516be0389f1da8ff6ea1531edc5afcd8f53` |
| `screenshots/ai-stabilizing-blue-line.jpeg` | E541 — blue stabilizing-value line. | `546e4defae35d2d65c37651dee853c12cf3a5f1e` |
| `screenshots/ai-lines-cross-no-longer-useful.jpeg` | E542 — threshold crossing / Juliette no longer useful. | `9a2a78cf8f47dc719ad2dd486a50bdf291924a68` |
| `screenshots/ai-removal-catastrophic-destabilization.jpeg` | E543 — abrupt removal may catastrophically destabilize Silo. | `982776864fd638f4f88e5e305233f55e2bbd2eaf` |
| `screenshots/ai-vitamins-before-removal.jpeg` | E544–E546 — vitamins planned before possible removal. | `f4a6a1d559b83d0f170108291a0df34aac4ff651` |
| `screenshots/ai-vitamins-water-supply.jpeg` | E544–E546 — water-supply population-scale deployment. | `c2e23738f90f1b18925d7b5c1becded3b45c096d` |

Contact sheet Git blob SHA: `e5e1aa786ca4220b3ef236c6ccccc72c4b88c5a2`.

## Validation

Всички 15 screenshots + contact sheet са валидирани byte-for-byte чрез Git blob SHA comparison срещу локално подготвения package преди analysis PR-а.

`contact-sheet.jpg` е auxiliary/navigation asset, не primary evidence.
