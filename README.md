# Проект SILO — reverse engineering на Engineered Survival System

Дневник за систематичен, evidence-driven и spoiler-disciplined анализ на телевизионния сериал **Silo**.

Целта е да третираме света на сериала като **черна кутия**: наблюдаваме поведението на системата, извличаме възможни правила, строим competing hypotheses и ги променяме или отхвърляме, когато нови епизоди дадат по-добър evidence.

> **Името `Engineered-Survival-System` започна като работна hypothesis. След S01E03 Силозът изглежда като layered habitation/control system, в която current residents поддържат operational layers, без да разбират непременно original/deeper source layers — както при history, така и при energy infrastructure.**

## Език на проекта

Основният език на repo-то е **български**.

Всички обяснителни текстове, анализи, conclusions, въпроси и описания се пишат на български. Утвърдени технически термини могат да останат на английски, когато това прави модела по-точен или по-четим — например `evidence`, `confidence`, `hypothesis`, `knowledge boundary`, `direct observation`, `institutional claim`, `visual pipeline`, `feed`, `overlay`, `falsification`, `branch` и `PR`.

Имената на файлове, branch-ове, code identifiers и оригинални UI/file labels от сериала не се превеждат задължително.

## Knowledge boundary

**Текуща граница на знанието:** **S01E03**

**Статус на гледане:** **Сезон 1, епизод 3**

Не се използва никаква информация от S01E04+, книгите, wiki, interviews, бъдещи synopses, leaks или retrospective explanations.

## Текущо състояние

След S01E03 най-силният работен модел е:

> **Силозът е 144-level engineered habitation system с приблизително 10 000 жители, силно vertical social structure, контролирани information/communication channels, hidden sub-Silo construction layer и exterior visual pipeline, който доказано може да показва radically different visual states.**

Ключови установени линии:

- cleaner lush view остава repeatable при Allison, Jane Carmody и Holston;
- public feed normally показва barren exterior;
- при S01E03 power-down **public display за момент показва lush exterior imagery**;
- това доказва multiple visual states в public-display pipeline-а, но не доказва кой state е real;
- Silo има **144 levels**, приблизително **10 000 residents** и regional structure `Up-top / Mids / Down-deep`;
- Level 50 е Mids и включва significant medical/neonatal infrastructure;
- Judicial е strongly localized на/около Level 14 чрез adjacent-shot evidence;
- Juliette family history показва, че vertical travel time създава de facto social separation;
- suicide се третира като serious crime against Silo;
- unauthorized/homemade radio е строго забранено от Pact;
- IT/Bernard се противопоставя на Juliette като Sheriff;
- Mayor подкрепя/утвърждава Juliette след Holston nomination-а;
- `SILOMAIL` е centralized digital messaging system;
- energy chain-ът е `steam from below → turbine → generator → Silo electricity`;
- current Mechanical personnel не знаят origin-а на primary steam source-а;
- Mayor умира след apparent deliberate attack/poisoning; motive и perpetrator остават неизвестни.

Подробният snapshot е в [`CURRENT_STATE.md`](CURRENT_STATE.md).

## Карта на repo-то

- [`CURRENT_STATE.md`](CURRENT_STATE.md) — кратък текущ модел след последния изгледан епизод.
- [`docs/episodes/S01E01.md`](docs/episodes/S01E01.md) — episode record за S01E01.
- [`docs/episodes/S01E02.md`](docs/episodes/S01E02.md) — episode record за S01E02.
- [`docs/episodes/S01E03.md`](docs/episodes/S01E03.md) — episode record за S01E03.
- [`docs/evidence-ledger.md`](docs/evidence-ledger.md) — evidence регистър с confidence и epistemic class.
- [`docs/evidence/S01E01-exterior-visual-contradiction.md`](docs/evidence/S01E01-exterior-visual-contradiction.md) — focused exterior evidence след S01E01.
- [`docs/evidence/S01E02-holston-visual-split.md`](docs/evidence/S01E02-holston-visual-split.md) — simultaneous cleaner/public visual split при Holston.
- [`docs/evidence/S01E02-sub-silo-construction-layer.md`](docs/evidence/S01E02-sub-silo-construction-layer.md) — hidden construction layer под Силоза.
- [`docs/evidence/S01E03-public-display-powerdown-flash.md`](docs/evidence/S01E03-public-display-powerdown-flash.md) — lush visual state на public display при power-down.
- [`docs/open-questions.md`](docs/open-questions.md) — активните въпроси за falsification / future testing.
- [`assets/S01E01/screenshots/`](assets/S01E01/screenshots/) — visual evidence от S01E01.
- [`assets/S01E02/screenshots/`](assets/S01E02/screenshots/) — selected visual evidence от S01E02.
- [`assets/S01E03/screenshots/`](assets/S01E03/screenshots/) — selected visual evidence от S01E03.

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

S01E03 прави това разграничение още по-важно: един и същ public display може да покаже barren state и lush state при различни system conditions.

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

След S01E03 все още не избираме окончателно една версия:

1. **Lush exterior is real** — public display-ът е false/manipulated.
2. **Barren exterior is substantially real** — cleaner helmet view е overlay/simulation.
3. **Neither is fully authentic** — и двата visual channels са processed representations.

S01E03 добавя critical constraint: lush imagery може да се появи и на **public display** при power-down. Това strengthens manipulation/state-switch model-а, но не authenticates нито едната exterior reality.

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

## Energy model

```text
UNKNOWN STEAM SOURCE BELOW
          │
          ▼
       TURBINE
          │
          ▼
      GENERATOR
          │
          ▼
   SILO ELECTRICITY
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
episode/S01E03
hypothesis/<name>
model/<name>
methodology/<change>
```

Git history е част от разследването: трябва да можем да видим кога е възникнала една theory, кой evidence я е укрепил, кой я е отслабил и кога е била refactor-ната или отхвърлена.

---

**Следваща knowledge boundary:** `S01E04`
