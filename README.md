# Проект SILO — reverse engineering на Engineered Survival System

Дневник за систематичен, evidence-driven и spoiler-disciplined анализ на телевизионния сериал **Silo**.

Целта е да третираме света на сериала като **черна кутия**: наблюдаваме поведението на системата, извличаме възможни правила, строим competing hypotheses и ги променяме или отхвърляме, когато нови епизоди дадат по-добър evidence.

> **След S01E07 моделът включва centralized covert surveillance under Sims operational command, concealed mirror cameras, privileged preservation на selected pre-Silo knowledge, Flamekeeper historical-preservation networks и confirmed covert reproductive-control deception.**

## Език на проекта

Основният език на repo-то е **български**.

Всички обяснителни текстове, анализи, conclusions, въпроси и описания се пишат на български. Утвърдени технически термини могат да останат на английски, когато това прави модела по-точен или по-четим — например `evidence`, `confidence`, `hypothesis`, `knowledge boundary`, `direct observation`, `institutional claim`, `visual pipeline`, `feed`, `overlay`, `falsification`, `branch` и `PR`.

Имената на файлове, branch-ове, code identifiers и оригинални UI/file labels от сериала не се превеждат задължително.

## Knowledge boundary

**Текуща граница на знанието:** **S01E07**

**Статус на гледане:** **Сезон 1, епизод 7**

Не се използва никаква информация от S01E08+, книгите, wiki, interviews, бъдещи synopses, leaks или retrospective explanations.

## Текущо състояние

След S01E07 най-силният работен модел е:

> **Силозът е 144-level engineered habitation/control system с dynamic exterior visual pipeline, hidden lower infrastructure, centralized covert surveillance under Sims operational command, restricted historical knowledge, Flamekeeper preservation networks и confirmed covert reproductive-control deception.**

Ключови установени линии:

- cleaner lush view остава repeatable при Allison, Jane Carmody и Holston;
- public display normally показва barren exterior;
- S01E03 power-down показва lush state на самия public display;
- S01E04 показва normal night state;
- S01E05 показва systematic/time-dependent star-like movement на night display-а;
- observer в cafeteria не знае concept-а „stars“ и сам reconstruct-ва movement patterns;
- Silo има **144 levels** и Bernard заявява **10 112 current residents**;
- observed level anchors вече включват `8, 9, 12, ~14, 27, 29, 50`;
- Pact deliberately забранява mechanized transport през Silo;
- Pact забранява magnifying devices над определен threshold;
- Juliette dossier съдържа content от разговора ѝ с Holston → strong hidden-surveillance/reporting evidence;
- Douglas Trumbull е хванат да manipulate/plant evidence и се опитва да убие Juliette;
- Sims лично убива Trumbull, после представя смъртта му като suicide;
- Judge formal closure-ва case-а след този false narrative;
- следователно official institutional record не може автоматично да се третира като independently established truth;
- Juliette търси formal hook за reopening на George case-а и взема PEZ relic-а от sub-Silo area;
- `The Syndrome` е explicit in-world term; S01E06 establishes new Deputy като concrete affected character, но nature/cause остават unknown;
- **няма established Syndrome ↔ magnification link** — това остава VL speculation/open question only;
- centralized multi-feed surveillance control center наблюдава множество internal locations, включително Juliette в дома ѝ;
- restricted Judicial relic database пази archival `PRE-SILO` records и Sims/Judicial има privileged access;
- pre-Silo Georgia travel guide establishes concrete U.S.-Georgia geography, но не locates the Silo;
- Sims operationally commands surveillance; Judge Meadows и medical center са monitored;
- concealed cameras са confirmed behind/in mirrors, а control-center access минава през hidden janitorial-closet route;
- Flamekeepers са described as preserving history/relics; exact relation to Rebellion remains unresolved;
- historical testimony introduces pre-Rebellion memory suppression through water;
- Juliette’s father personally admits implant-removal deception, confirming the covert reproductive-control mechanism;
- Juliette and George are linked through their Flamekeeper mothers and an intergenerational preservation network;
- observed level anchors now also include Level 26.

Подробният snapshot е в [`CURRENT_STATE.md`](CURRENT_STATE.md).

## Карта на repo-то

- [`CURRENT_STATE.md`](CURRENT_STATE.md) — текущ модел след последния изгледан епизод.
- [`docs/episodes/S01E01.md`](docs/episodes/S01E01.md) — episode record за S01E01.
- [`docs/episodes/S01E02.md`](docs/episodes/S01E02.md) — episode record за S01E02.
- [`docs/episodes/S01E03.md`](docs/episodes/S01E03.md) — episode record за S01E03.
- [`docs/episodes/S01E04.md`](docs/episodes/S01E04.md) — episode record за S01E04.
- [`docs/episodes/S01E05.md`](docs/episodes/S01E05.md) — episode record за S01E05.
- [`docs/episodes/S01E06.md`](docs/episodes/S01E06.md) — episode record за S01E06.
- [`docs/episodes/S01E07.md`](docs/episodes/S01E07.md) — episode record за S01E07.
- [`docs/evidence-ledger.md`](docs/evidence-ledger.md) — evidence регистър с confidence и epistemic class.
- [`docs/evidence/S01E01-exterior-visual-contradiction.md`](docs/evidence/S01E01-exterior-visual-contradiction.md) — focused exterior evidence след S01E01.
- [`docs/evidence/S01E02-holston-visual-split.md`](docs/evidence/S01E02-holston-visual-split.md) — simultaneous cleaner/public visual split при Holston.
- [`docs/evidence/S01E02-sub-silo-construction-layer.md`](docs/evidence/S01E02-sub-silo-construction-layer.md) — hidden construction layer под Silo.
- [`docs/evidence/S01E03-public-display-powerdown-flash.md`](docs/evidence/S01E03-public-display-powerdown-flash.md) — lush state на public display при power-down.
- [`docs/evidence/S01E04-sheriff-succession-and-control.md`](docs/evidence/S01E04-sheriff-succession-and-control.md) — Judicial/IT opposition и Sheriff succession conflict.
- [`docs/evidence/S01E05-surveillance-trumbull-coverup.md`](docs/evidence/S01E05-surveillance-trumbull-coverup.md) — surveillance, framing, Trumbull и false suicide narrative.
- [`docs/evidence/S01E05-celestial-observation.md`](docs/evidence/S01E05-celestial-observation.md) — star-like temporal behavior и lost astronomical knowledge.
- [`docs/evidence/S01E05-pact-capability-restrictions.md`](docs/evidence/S01E05-pact-capability-restrictions.md) — mechanized-transport и magnification restrictions.
- [`docs/evidence/S01E06-centralized-surveillance.md`](docs/evidence/S01E06-centralized-surveillance.md) — direct-confirmed centralized internal surveillance.
- [`docs/evidence/S01E06-relic-database-pre-silo.md`](docs/evidence/S01E06-relic-database-pre-silo.md) — PEZ lookup, Judicial relic DB и preserved pre-Silo knowledge.
- [`docs/evidence/S01E06-georgia-relic.md`](docs/evidence/S01E06-georgia-relic.md) — Georgia, USA pre-Silo geography clue.
- [`docs/evidence/S01E07-surveillance-command-and-mirrors.md`](docs/evidence/S01E07-surveillance-command-and-mirrors.md) — Sims command, mirror cameras и concealed surveillance architecture.
- [`docs/evidence/S01E07-flamekeepers-memory-erasure.md`](docs/evidence/S01E07-flamekeepers-memory-erasure.md) — Flamekeepers, relic preservation и water-memory claim.
- [`docs/evidence/S01E07-reproductive-control.md`](docs/evidence/S01E07-reproductive-control.md) — doctor confession и reproductive-control mechanism.
- [`docs/evidence/S01E07-flamekeeper-family-network.md`](docs/evidence/S01E07-flamekeeper-family-network.md) — Juliette/George intergenerational Flamekeeper connection.
- [`docs/open-questions.md`](docs/open-questions.md) — активните въпроси за falsification / future testing.
- [`assets/S01E01/screenshots/`](assets/S01E01/screenshots/) — visual evidence от S01E01.
- [`assets/S01E02/screenshots/`](assets/S01E02/screenshots/) — selected visual evidence от S01E02.
- [`assets/S01E03/screenshots/`](assets/S01E03/screenshots/) — selected visual evidence от S01E03.
- [`assets/S01E04/screenshots/`](assets/S01E04/screenshots/) — selected visual evidence от S01E04.
- [`assets/S01E05/screenshots/`](assets/S01E05/screenshots/) — selected visual evidence от S01E05.

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

### Допълнително правило след S01E05

**Official record ≠ independently verified truth.**

S01E05 дава direct-confirmed example: Sims kills Trumbull → official narrative says suicide → Judge closes case.

Това не означава, че всички official records са false. Означава, че official records се класифицират като institutional claims, когато няма independent corroboration.

### Допълнително правило след S01E06

**Public knowledge loss ≠ total institutional knowledge loss.** Restricted relic DB показва, че selected pre-Silo records са preserved в privileged systems. Hidden surveillance също вече е direct-confirmed infrastructure, а не само dossier inference.

### Допълнително правило след S01E07

**Direct confession / direct observation > historical explanation.**

S01E07 съдържа както direct-confirmed механизми, така и historical testimony. Например:
- retained-implant deception е independently corroborated чрез Allison physical evidence + Juliette’s father confession;
- water-based memory suppression и anti-Flamekeeper lineage targeting остават historical claims до independent corroboration;
- Flamekeepers не се приравняват автоматично с Rebels, докато episode evidence не establish-не връзката.

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
- fan theories, които използват future knowledge;
- retrospective knowledge, което прави стара theory да изглежда по-силна, отколкото е била при формулирането ѝ.

Спекулативни cross-links се маркират изрично. Например `The Syndrome ↔ magnification ban` към S01E05 е **VL speculation only**, не accepted theory.

## Слоеве на анализа

### Физическа система

Архитектура, infrastructure, resources, energy, air, water, production, maintenance, technological limits и physical boundaries.

### Система на управление

Institutions, laws, prohibitions, hierarchy, enforcement, punishment, investigation и реално срещу формално разпределение на властта.

### Информационна система

Access, surveillance, dossiers, forbidden knowledge, archives, historical memory, communications, education и possible information manipulation.

### Capability-control system

Какво residents физически могат да правят/наблюдават: vertical movement, radios, magnification, access to restricted spaces и tools за independent discovery.

### Социална система

Population, reproduction, profession, level structure, social mobility, trust, fear, norms и inter-level relations.

### Material/resource system

Ownership, assignment, recycling, redistribution, scarcity и closed-loop use на durable goods.

### Survival system

Разделяме правилата, които реално може да са необходими за survival, от правилата, които може да служат на institutional control.

### Модел на външния свят

**това, в което героите вярват ≠ това, което властите твърдят ≠ това, което показва екранът ≠ това, което е обективно установено**

След S01E05 public display има normal day/night states, systematic celestial temporal behavior и abnormal lush power-down state.

## Evidence класове

- **Direct observation** — сериалът директно показва събитието/обекта.
- **Repeated observation** — поведението/моделът се появява независимо повече от веднъж.
- **Character testimony** — доказва какво твърди/вярва герой, не непременно че твърдението е вярно.
- **Institutional claim** — официално правило, historical account или case conclusion; третира се като claim до независимо потвърждение.
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

След S01E07 все още не избираме окончателно една версия:

1. **Lush exterior is real** — public display-ът е false/manipulated.
2. **Barren exterior is substantially real** — cleaner helmet view е overlay/simulation.
3. **Neither is fully authentic** — и двата visual channels са processed representations.

Systematic star-like movement прави public night state по-сложен/dynamic, но не го authenticates като live physical sky.

## Текущ architectural model

```text
LEVEL 1 / UP-TOP ?
        │
        ├─ Sheriff's Department ?
        └─ secure airlock / cleaning access ?
        │
        ▼
LEVEL 8 → 9 → 12 → ~14 JUDICIAL → 17 → 26 → 27 → 29
        │
        ▼
LEVEL 50 / MIDS
        │
        ▼
DOWN-DEEP
        │
        │  144 inhabited levels total
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
        ├─ George cache / PEZ trail
        └─ flooded bottom
               │
               └─ reported short tunnel + door ?
```

Question marks означават strong spatial inference, не single-frame direct confirmation.

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
episode/S01E03
episode/S01E04
episode/S01E05-analysis
episode/S01E06-analysis
episode/S01E07
hypothesis/<name>
model/<name>
methodology/<change>
```

Git history е част от разследването: трябва да можем да видим кога е възникнала една theory, кой evidence я е укрепил, кой я е отслабил и кога е била refactor-ната или отхвърлена.

---

**Следваща knowledge boundary:** `S01E08`
