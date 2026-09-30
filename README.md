# Проект SILO — reverse engineering на Engineered Survival System

Дневник за систематичен, evidence-driven и spoiler-disciplined анализ на телевизионния сериал **Silo**.

Целта е да третираме света на сериала като **черна кутия**: наблюдаваме поведението на системата, извличаме възможни правила, строим competing hypotheses и ги променяме или отхвърляме, когато нови епизоди дадат по-добър evidence.

> **Името `Engineered-Survival-System` започна като работна hypothesis. След S01E01 самото наличие на engineered survival infrastructure е силно подкрепено; предназначението и честността на управляващия режим остават отворени въпроси.**

## Език на проекта

Основният език на repo-то е **български**.

Всички обяснителни текстове, анализи, conclusions, въпроси и описания се пишат на български. Утвърдени технически термини могат да останат на английски, когато това прави модела по-точен или по-четим — например `evidence`, `confidence`, `hypothesis`, `knowledge boundary`, `direct observation`, `institutional claim`, `visual pipeline`, `feed`, `overlay`, `falsification`, `branch` и `PR`.

Имената на файлове, branch-ове, code identifiers и оригинални UI/file labels от сериала не се превеждат задължително.

## Knowledge boundary

**Текуща граница на знанието:** **S01E01**

**Статус на гледане:** **Сезон 1, епизод 1**

Не се използва никаква информация от S01E02+, книгите, wiki, interviews, бъдещи synopses, leaks или retrospective explanations.

## Текущо състояние

След S01E01 най-силният работен извод е:

> **Обитателите на Силоза живеят не само в затворена физическа среда, а и в контролирана информационна система. Външният свят не може да бъде независимо наблюдаван: публичният екран показва мъртва среда, докато Allison Becker и старият `Jane Carmody Cleaning` запис показват зелена среда. Поне една част от visual pipeline-а е манипулирана или заменена, но още не знаем коя.**

Ключови установени линии:

- population control чрез reproductive permits и contraceptive implants;
- доказан поне един случай на скрито несъответствие между разрешение за репродукция и реално премахване на импланта;
- забранени relics и ограничено historical/technical knowledge;
- официална история, която обвинява rebellion-а за унищожените архиви;
- IT контрол върху digital infrastructure и потиснато knowledge за възстановяване на изтрити файлове;
- HDD **18** с възстановени historical/engineering files;
- blueprint-и на Силоза с **classified lower tunnel**;
- несъвместими exterior images;
- cleaning ritual, при който Allison чисти, след като вижда зелената версия, въпреки предварителното си намерение;
- Allison впоследствие пада до дървото — причината остава неизвестна;
- Juliette Nichols оспорва официалната версия за смъртта на George Wilkins.

Подробният snapshot е в [`CURRENT_STATE.md`](CURRENT_STATE.md).

## Карта на repo-то

- [`CURRENT_STATE.md`](CURRENT_STATE.md) — кратък текущ модел след последния изгледан епизод.
- [`docs/episodes/S01E01.md`](docs/episodes/S01E01.md) — пълният episode record за S01E01.
- [`docs/evidence-ledger.md`](docs/evidence-ledger.md) — evidence регистър с confidence и epistemic class.
- [`docs/open-questions.md`](docs/open-questions.md) — активните въпроси за falsification / future testing.
- [`assets/S01E01/screenshots/`](assets/S01E01/screenshots/) — visual evidence от S01E01.

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
- ретроспективно знание, което прави стара theory да изглежда по-силна, отколкото е била в момента на формулирането ѝ.

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

S01E01 показва защо това разграничение е критично.

## Evidence класове

- **Direct observation** — сериалът директно показва събитието/обекта.
- **Repeated observation** — поведението/моделът се появява независимо повече от веднъж.
- **Character testimony** — доказва какво твърди/вярва герой, не непременно че твърдението е вярно.
- **Institutional claim** — официално правило или исторически разказ; третира се като claim до независимо потвърждение.
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

След S01E01 не избираме преждевременно една версия:

1. **Зеленият външен свят е реален** — публичният екран е измама.
2. **Мъртвият външен свят е реален** — cleaner helmet view е overlay/simulation.
3. **Нито един feed не е напълно автентичен** — и двата visual channels са processed representations.

Тези models трябва да бъдат тествани срещу следващите епизоди.

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
10. Правим PR, който запазва exact knowledge state след този епизод.

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

**Следваща knowledge boundary:** `S01E02`
