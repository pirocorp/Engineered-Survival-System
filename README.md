# Проект SILO — reverse engineering на Engineered Survival System

Дневник за систематичен, evidence-driven и spoiler-disciplined анализ на телевизионния сериал **Silo**.

Целта е да третираме света на сериала като **черна кутия**: наблюдаваме поведението на системата, извличаме възможни правила, строим competing hypotheses и ги променяме или отхвърляме, когато нови епизоди дадат по-добър evidence.

> **Името `Engineered-Survival-System` започна като работна hypothesis. След S01E02 вече е ясно, че Силозът е силно engineered habitation/control system, изградена върху по-стар construction layer. Survival purpose-ът, exterior reality и истинската история на системата остават отворени.**

## Език на проекта

Основният език на repo-то е **български**.

Всички обяснителни текстове, анализи, conclusions, въпроси и описания се пишат на български. Утвърдени технически термини могат да останат на английски, когато това прави модела по-точен или по-четим — например `evidence`, `confidence`, `hypothesis`, `knowledge boundary`, `direct observation`, `institutional claim`, `visual pipeline`, `feed`, `overlay`, `falsification`, `branch` и `PR`.

Имената на файлове, branch-ове, code identifiers и оригинални UI/file labels от сериала не се превеждат задължително.

## Knowledge boundary

**Текуща граница на знанието:** **S01E02**

**Статус на гледане:** **Сезон 1, епизод 2**

Не се използва никаква информация от S01E03+, книгите, wiki, interviews, бъдещи synopses, leaks или retrospective explanations.

## Текущо състояние

След S01E02 най-силният работен модел е:

> **Силозът е 144-level engineered habitation system, в която exterior information се подава през несъвместими visual channels, а под официалното Down-deep има скрит Pact-restricted pre-Rebellion construction layer с excavation machine, flooded lower zone и вероятен lower tunnel/door endpoint.**

Ключови установени линии:

- cleaner lush view вече е repeatable при Allison, Jane Carmody и Holston;
- по време на Holston cleaning public feed-ът едновременно показва barren exterior;
- public feed-ът има поне partial physical corroboration — Holston достига Allison на мястото, където feed-ът я показва;
- Holston изпитва distress, сваля helmet-а и умира до Allison;
- exterior displays са част от broad public information infrastructure;
- Silo има **144 levels** и regional structure `Up-top / Mids / Down-deep`;
- Judicial/Sims има видима coercive тежест;
- post-Rebellion order е приблизително **140 години** стар;
- mayor journals стигат поне до `Year 97`, което силно свързва institutional chronology с `SILO YEAR 96/97` от HDD 18;
- Pact изрично забранява достъпа до част от lower infrastructure;
- зад restriction-а има pre-Rebellion tunnel system и скрит достъп под inhabited Silo;
- под Down-deep има sealed construction cavity с огромна excavation machine и flooded bottom;
- George е поддържал hidden workspace/cache там;
- cache-ът съдържа HDD 18, deleted-file recovery material, relic video camera и документ с handwriting на Allison;
- George е търсил lower door и оставя message, че е намерил това, което търси;
- Holston номинира Juliette за successor като Sheriff и оставя badge-а си за нея.

Подробният snapshot е в [`CURRENT_STATE.md`](CURRENT_STATE.md).

## Карта на repo-то

- [`CURRENT_STATE.md`](CURRENT_STATE.md) — кратък текущ модел след последния изгледан епизод.
- [`docs/episodes/S01E01.md`](docs/episodes/S01E01.md) — episode record за S01E01.
- [`docs/episodes/S01E02.md`](docs/episodes/S01E02.md) — episode record за S01E02.
- [`docs/evidence-ledger.md`](docs/evidence-ledger.md) — evidence регистър с confidence и epistemic class.
- [`docs/evidence/S01E01-exterior-visual-contradiction.md`](docs/evidence/S01E01-exterior-visual-contradiction.md) — focused exterior evidence след S01E01.
- [`docs/evidence/S01E02-holston-visual-split.md`](docs/evidence/S01E02-holston-visual-split.md) — simultaneous cleaner/public visual split при Holston.
- [`docs/evidence/S01E02-sub-silo-construction-layer.md`](docs/evidence/S01E02-sub-silo-construction-layer.md) — hidden construction layer под Силоза.
- [`docs/open-questions.md`](docs/open-questions.md) — активните въпроси за falsification / future testing.
- [`assets/S01E01/screenshots/`](assets/S01E01/screenshots/) — visual evidence от S01E01.
- [`assets/S01E02/screenshots/`](assets/S01E02/screenshots/) — selected visual evidence от S01E02.

## Основна директива

**Observation → Rule → Evidence → Confidence → Open Questions → Hypothesis**

Не започваме с теория и не принуждаваме observations да ѝ пасват.

Разделяме ясно:

- какво действително сме видели;
- какво героите твърдят;
- какво институциите твърдят;
- какво системата изглежда предполага;
- какво ние извеждаме като правило;
- какво остава само hypothesis.

## Spoiler discipline

Анализът е ограничен до вече изгледаното съдържание.

Разрешено е:

- информация от епизоди до текущата knowledge boundary;
- повторно анализиране на вече видени сцени и screenshots;
- сравняване на observations от предишни епизоди;
- собствени логически изводи и competing hypotheses.

Не се използват, освен ако изрично не бъде поискано:

- бъдещи епизоди;
- книгите;
- wiki информация отвъд текущия епизод;
- interviews с бъдещи reveals;
- synopsis-и на неизгледани епизоди;
- leaks;
- fan theories, които използват бъдещо knowledge;
- retrospective knowledge, което прави стара theory да изглежда по-силна, отколкото е била при формулирането ѝ.

## Слоеве на анализа

### Физическа система

Архитектура, infrastructure, resources, energy, air, water, production, maintenance, technological limits и physical boundaries.

### Система на управление

Institutions, laws, prohibitions, hierarchy, enforcement, punishment и реално срещу формално разпределение на властта.

### Информационна система

Access, forbidden knowledge, archives, historical memory, communications, education и possible information manipulation.

### Социална система

Population, reproduction, profession, level structure, social mobility, trust, fear, norms и inter-level relations.

### Survival system

Разделяме правилата, които реално може да са необходими за survival, от правилата, които може да служат на institutional control.

### Модел на външния свят

За външния свят важи особено строг принцип:

**това, в което героите вярват ≠ това, което властите твърдят ≠ това, което показва екранът ≠ това, което е обективно установено**

S01E02 прави това разграничение още по-важно, защото Holston cleaning показва simultaneous incompatible visual channels.

## Evidence класове

- **Direct observation** — сериалът директно показва събитието/обекта.
- **Repeated observation** — поведението/моделът се появява независимо повече от веднъж.
- **Character testimony** — доказва какво твърди/вярва герой, не непременно че твърдението е вярно.
- **Institutional claim** — официално правило или historical account; третира се като claim до независимо потвърждение.
- **Visual/screenshot evidence** — детайл в кадър, файл, blueprint, UI или archive listing.
- **Inference** — логически извод от evidence.
- **Speculation** — възможно обяснение без достатъчна evidence support.

## Confidence

| Confidence | Значение |
|---|---|
| **VH** | Много силно подкрепена от множество независими observations |
| **H** | Силно подкрепена, но остават реални алтернативи |
| **M** | Правдоподобна и подкрепена частично |
| **L** | Възможна, но evidence е слаб или косвен |
| **VL** | Почти чиста speculation |

Confidence не е математическа вероятност и не замества evidence.

## Hypothesis lifecycle

**Candidate → Active → Strengthened → Weakened → Refactored → Rejected → Confirmed**

`Confirmed` се използва пестеливо.

Ако нова информация опровергава само част от theory, предпочитаме **refactor**, вместо да я защитаваме на всяка цена.

## Текущи competing models за външния свят

След S01E02 не избираме окончателно една версия:

1. **Lush exterior is real** — public display-ът е false/manipulated.
2. **Barren exterior is substantially real** — cleaner helmet view е overlay/simulation.
3. **Neither is fully authentic** — и двата visual channels са processed representations.

Model 2 е strengthened след Holston cleaning, защото public feed-ът правилно локализира Allison като physical object. Но липсва direct POV след helmet removal, затова model-ът още не е `Confirmed`.

## Текущ architectural model

```text
UP-TOP / MIDS / DOWN-DEEP
        │
        │  144 inhabited levels
        ▼
STRUCTURAL BOTTOM / CAP
        │
        ▼
PACT-FORBIDDEN PRE-REBELLION TUNNEL
        │
        ▼
SUB-SILO CONSTRUCTION CAVITY
        │
        ├─ excavation machine
        ├─ lower machine/service levels
        └─ flooded bottom
               │
               └─ reported short tunnel + door ?
```

## Workflow след всеки епизод

1. Записваме новите observations.
2. Отделяме facts от character/institutional claims.
3. Добавяме visual evidence.
4. Проверяваме recurring patterns.
5. Актуализираме rules и active hypotheses.
6. Променяме confidence само с конкретна причина.
7. Записваме contradictions.
8. Добавяме open questions.
9. Определяме какво би falsify-нало важните theories.
10. Правим PR, който запазва exact knowledge state след този episode.

## Git / PR философия

`main` представлява текущото прието състояние на модела.

Промените след отделните епизоди минават през отделни branches/PRs:

```text
episode/S01E01
episode/S01E02
hypothesis/<name>
model/<name>
methodology/<change>
```

Git history е част от разследването: трябва да можем да видим кога е възникнала една theory, кой evidence я е укрепил, кой я е отслабил и кога е била refactor-ната или отхвърлена.

---

**Следваща knowledge boundary:** `S01E03`
