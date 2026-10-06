# S03E09 manifest на визуалното evidence

Двоичните assets са качени в `main` с commit `b6f936411a365588ad48062e80a9a3e614525d5d` и присъстват в current `main` head `042e697bde1bf3af70979d6d7a1f4a613da5510d` преди analysis PR-а.

Спецификация за обработка:
- output: 1536×864 JPEG за selected screenshots;
- quality: 95;
- perspective correction / TV-plane rectification;
- без generative editing, reconstruction, subtitle removal или synthetic fill.

Git blob SHA стойностите по-долу са прочетени отново от `main` и съвпадат byte-for-byte с локално генерираните final assets.

## Primary screenshots

| Файл | Git blob SHA | Роля като evidence |
|---|---|---|
| `screenshots/bernard-voice-you-dont-know-more-goodbye.jpeg` | `63f92e7f2aa6167489b638f19e637eaeebc6ae4f` | Bernard challenges Voice epistemic authority |
| `screenshots/camille-voice-ended-conversation-anger.jpeg` | `a051d2858d18e1406d8a8889a23813c85597b888` | Camille interprets Voice reaction |
| `screenshots/level-144-crowd-stairwell.jpeg` | `4fe544e38d448dbbe1fcbf83321ffce13b9078a5` | Level 144 / public crowd context |
| `screenshots/bernard-outside-without-suit.jpeg` | `c4b12fcd69daa4b2a027afb58bdb224f3de0c8cf` | Bernard alive outside without protective suit |
| `screenshots/bernard-no-suit-exterior-observed-from-silo.jpeg` | `6ba91209b9e37afa1ab28f4ecbdd1973a8e37a31` | wider no-suit exterior / internal-observer context |
| `screenshots/silo-complex-opening-ceremony-aerial.jpeg` | `3212c0d8837975b9a5062536444f6444170cecdc` | official opening/intake establishing view |
| `screenshots/opening-map-silos-1-to-50-topology.jpeg` | `5174336c621d83a6d0dfc0b77d97d8cb62020c22` | numbered opening map, Silos 1–50 |
| `screenshots/full-silo-complex-aerial-topology.jpeg` | `1154d5ac7e33465e5b68e1023d451a5994cf3d64` | full physical topology / clusters |
| `screenshots/daniel-parents-sit-still-be-patient-message.jpeg` | `85710332fdc3cf0dc2e599800bd1491b7b811331` | parents message immediately before catastrophe |
| `screenshots/silo-opening-nuclear-detonation.jpeg` | `246d59361eb1953ec14a356a9365e04f6b4ee6e3` | nuclear event with opening-day situational context |
| `screenshots/opening-day-nuclear-mushroom-cloud.jpeg` | `dce7a8c0d33c9246181127ccfd27e7c869772297` | clearest mushroom-cloud visual |

## Supporting / navigation

| Файл | Git blob SHA | Роля |
|---|---|---|
| `screenshots/opening-day-message-sitting-next-to-anna.jpeg` | `7472fb8bbfd598ac1d7668bc06bca3532ce7fdff` | opening-day personal communication |
| `screenshots/S03E09-contact-sheet.jpeg` | `e0570a8c8253661372de551630e415fb7740e20d` | навигационен contact sheet |

Всички 13 файла в `assets/S03E09/screenshots/` са валидирани срещу Git blob SHA на `main`.
