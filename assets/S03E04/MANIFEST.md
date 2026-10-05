# S03E04 visual evidence manifest

**Knowledge boundary:** `S03E04`

Binary assets са качени в `main` преди този text-only analysis PR.

## Правила за обработка

- perspective correction на photographed TV plane;
- output normalized до `1536×864`;
- JPEG quality 95;
- без generative editing;
- без content reconstruction, object removal или synthetic fill;
- visible scene content е запазено;
- без external/future-episode sources.

## Selected frames

| File | Evidence / context | Git blob SHA |
|---|---|---|
| `screenshots/abyss-hidden-route-rope-descent.jpeg` | E650–E657, E661–E663 — concealed deep-zone route, tunnel и fixed rope/descent access. | `e4cdc07e4448058d5659da7faaa6150644e3cdee` |
| `screenshots/bernard-alive-deep-zone.jpeg` | E664–E669 — Bernard alive in deep zone; major correction на prior death/burning account. | `21bc13bc33e27eadef1722d9abee63d9a51a3277` |

Contact sheet Git blob SHA: `9c6f7d0ee69f382ab6169b33e44236b785b4d4ef`.

## Validation

Всички **2 screenshots + contact sheet** са валидирани byte-for-byte чрез Git blob SHA comparison спрямо локално подготвения package преди analysis PR-а.

`contact-sheet.jpg` е auxiliary/navigation asset, не primary evidence.
