# S03E09 — Манифест на визуалните доказателства

Двоичните ресурси са качени в `main` с commit `b6f936411a365588ad48062e80a9a3e614525d5d` и присъстват в тогавашния `main` head `042e697bde1bf3af70979d6d7a1f4a613da5510d` преди PR-а за анализ.

Спецификация за обработка:
- изходен формат: JPEG 1536×864 за избраните екранни снимки;
- качество: 95;
- корекция на перспективата / ректификация спрямо равнината на телевизионния екран;
- без генеративно редактиране, реконструкция, премахване на субтитри или синтетично запълване.

Git blob SHA стойностите по-долу са прочетени повторно от `main` и съвпадат байт по байт с локално генерираните крайни файлове.

## Основни екранни снимки

| Файл | Git blob SHA | Роля като доказателство |
|---|---|---|
| `screenshots/bernard-voice-you-dont-know-more-goodbye.jpeg` | `63f92e7f2aa6167489b638f19e637eaeebc6ae4f` | Bernard оспорва епистемичния авторитет на „Гласът“ |
| `screenshots/camille-voice-ended-conversation-anger.jpeg` | `a051d2858d18e1406d8a8889a23813c85597b888` | Camille интерпретира реакцията на „Гласът“ |
| `screenshots/level-144-crowd-stairwell.jpeg` | `4fe544e38d448dbbe1fcbf83321ffce13b9078a5` | Ниво 144 / контекст с публично струпване |
| `screenshots/bernard-outside-without-suit.jpeg` | `c4b12fcd69daa4b2a027afb58bdb224f3de0c8cf` | Bernard е жив навън без защитен костюм |
| `screenshots/bernard-no-suit-exterior-observed-from-silo.jpeg` | `6ba91209b9e37afa1ab28f4ecbdd1973a8e37a31` | По-широк контекст на Bernard без костюм във външната среда / наблюдение от силоза |
| `screenshots/silo-complex-opening-ceremony-aerial.jpeg` | `3212c0d8837975b9a5062536444f6444170cecdc` | Установяващ кадър от официалното откриване/прием |
| `screenshots/opening-map-silos-1-to-50-topology.jpeg` | `5174336c621d83a6d0dfc0b77d97d8cb62020c22` | Номерирана карта при откриването, силози 1–50 |
| `screenshots/full-silo-complex-aerial-topology.jpeg` | `1154d5ac7e33465e5b68e1023d451a5994cf3d64` | Пълна физическа топология / групи |
| `screenshots/daniel-parents-sit-still-be-patient-message.jpeg` | `85710332fdc3cf0dc2e599800bd1491b7b811331` | Съобщение от родителите непосредствено преди катастрофата |
| `screenshots/silo-opening-nuclear-detonation.jpeg` | `246d59361eb1953ec14a356a9365e04f6b4ee6e3` | Ядрено събитие в контекста на деня на откриването |
| `screenshots/opening-day-nuclear-mushroom-cloud.jpeg` | `dce7a8c0d33c9246181127ccfd27e7c869772297` | Най-ясният визуален кадър на ядрената гъба |

## Поддържащи / навигационни материали

| Файл | Git blob SHA | Роля |
|---|---|---|
| `screenshots/opening-day-message-sitting-next-to-anna.jpeg` | `7472fb8bbfd598ac1d7668bc06bca3532ce7fdff` | Лична комуникация в деня на откриването |
| `screenshots/S03E09-contact-sheet.jpeg` | `e0570a8c8253661372de551630e415fb7740e20d` | Навигационен контактен лист |

Всички 13 файла в `assets/S03E09/screenshots/` са валидирани спрямо Git blob SHA в `main`.
