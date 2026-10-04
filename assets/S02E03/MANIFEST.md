# S02E03 visual evidence manifest

**Knowledge boundary:** `S02E03`

Този package съдържа само user-provided S02E03 TV photographs, обработени за archival use.

## Правила за обработка

- първо perspective correction / TV-plane rectification;
- output е normalized до `1536×864`;
- JPEG quality 95;
- без generative editing;
- без content reconstruction или object removal;
- без synthetic fill;
- source subtitles, glare/reflections и visible scene content са запазени;
- не са използвани external или future-episode sources.

## Selected frames

| Evidence | File | Bytes | Git blob SHA | Notes |
|---|---|---:|---|---|
| E243 | `screenshots/bernard-key18-server-room-access.jpeg` | 347940 | `cd7f74643eeea5f3e0ee10d450438ce4cae1098a` | Physical key 18 на Bernard е свързан с access до SERVER ROOM. |
| E244-E245 | `screenshots/server-room-it-vault.jpeg` | 252369 | `2bd4d6b5940237f4758fc7d148aa26a9d885f7fe` | В SERVER ROOM се намира heavy secured IT vault, което установява path-а key 18 -> Server Room -> vault. |
| E262-E263 | `screenshots/silo-orange-birth-control-protocol.jpeg` | 319855 | `d6f5c9626fecb733629ce7823d5e89712fdb561a` | Medical record показва CODE SILO ORANGE instructions да не се премахва birth control, докато пациентът вярва, че е премахнат; DOB използва A.R. notation. |

## Evidence boundaries

- E243: сцената установява, че physical key `18` на Bernard се използва за / е свързан с access до `SERVER ROOM`. Exact lock internals не се извеждат отвъд observed access sequence.
- E244–E245: secured vault е пространствено в Server Room и установява restricted path `key 18 -> Server Room -> vault`.
- E262: `CODE SILO ORANGE` explicitly инструктира medical staff да не премахва birth control, докато гарантира, че пациентът вярва, че е премахнат.
- E263: същият medical record директно показва `A.R.` date notation. Това подкрепя distinct institutional era notation, но само по себе си не разгръща `A.R.` textual като `After Rebellion`.
- E264 chronology conflict е text/model evidence и няма dedicated screenshot в този batch.
- Package-ът не установява visually numbering на Silo 17, 50-Silo count, failed cleaning на Ron, Silo 17 rebellion sequence, memory-suppression drug dialogue или bird-pattern inference на Juliette; те остават dialogue/scene-context evidence, освен ако по-късно не се добавят dedicated frames.

## Contact sheet

`contact-sheet.jpg` е auxiliary navigation asset, а не primary evidence.
