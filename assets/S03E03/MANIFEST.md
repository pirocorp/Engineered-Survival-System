# S03E03 visual evidence manifest

**Knowledge boundary:** `S03E03`

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
| `screenshots/vitamin-d-plus-water.jpeg` | E557–E563 — Vitamin D+ / water-supply memory-control context. | `64fde77af8afebb9a30685f61a386048a4fa10fb` |
| `screenshots/vitamin-d-plus-survival-chance.jpeg` | E557–E563 — system claims water deployment increases survival chance. | `e0e21628504bbaa4b43b2fc13e4fa91757351b91` |
| `screenshots/silo-close-to-safeguard.jpeg` | E558–E563 — Silo condition framed as close to safeguard. | `67e3eb0ca7aec4f354b48be342bf1cc1567c9263` |
| `screenshots/safeguard-cross-silo-contact-trigger.jpeg` | E564–E567 — cross-Silo contact → immediate safeguard. | `069e4f913c4eddbd2cca03f56d427378ea875ab5` |
| `screenshots/level-124.jpeg` | E568 — Level 124. | `3dda0dcc92acd828dad611cae26062759544acb2` |
| `screenshots/level-70-mine-access.jpeg` | E569–E572 — Level 70 / mine-sector access context. | `146fd2e3715969ec8cb255a7909c06fa95ab889b` |
| `screenshots/mine-interior.jpeg` | E573–E575 — direct mine environment. | `c313b8c01214920dd093c1a0d925f3b635b3bcc3` |
| `screenshots/camille-selected-for-lying.jpeg` | E589–E590 — Camille selected for ability to lie. | `fa8d8dcada50e0f319e0a1d9361185bf4efc96da` |
| `screenshots/head-of-it-role-built-on-deception.jpeg` | E594–E596 — deception fundamental to Head of IT role. | `cbe51847415a15915a4561a9db1c07f1582ba0f3` |

Contact sheet Git blob SHA: `223b2a1da6650ad99c5bcb067fbf3b01d6180214`.

## Validation

Всички 9 screenshots + contact sheet са валидирани byte-for-byte чрез Git blob SHA comparison срещу локално подготвения package преди analysis PR-а.

`contact-sheet.jpg` е auxiliary/navigation asset, не primary evidence.
