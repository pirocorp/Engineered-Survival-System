# Проект SILO — reverse engineering на Engineered Survival System

Дневник за систематичен, evidence-driven и spoiler-disciplined анализ на телевизионния сериал **Silo**.

Целта е да третираме света на сериала като **черна кутия**: наблюдаваме поведението на системата, извличаме възможни правила, строим competing hypotheses и ги променяме или отхвърляме, когато нови епизоди дадат по-добър evidence.

> **След S02E02 the hidden cleaning/control architecture is substantially clearer: Bernard receives a live Juliette-associated exterior feed, consults `THE ORDER`, which explicitly says `IN THE EVENT OF A FAILED CLEANING, PREPARE FOR WAR`, and insider dialogue strongly ties Juliette's survival to replacement of the standard cleaning tape with a better seal.**

## Език на проекта

Основният език на repo-то е **български**.

Всички обяснителни текстове, анализи, conclusions, въпроси и описания се пишат на български. Утвърдени технически термини могат да останат на английски, когато това прави модела по-точен или по-четим — например `evidence`, `confidence`, `hypothesis`, `knowledge boundary`, `direct observation`, `institutional claim`, `visual pipeline`, `feed`, `overlay`, `falsification`, `branch` и `PR`.

Имената на файлове, branch-ове, code identifiers и оригинални UI/file labels от сериала не се превеждат задължително.

## Knowledge boundary

**Текуща граница на знанието:** **S02E02**

**Статус на гледане:** **Сезон 2, епизод 2**

Не се използва никаква информация от S02E03+, книгите, wiki, interviews, бъдещи synopses, leaks или retrospective explanations.

## Текущо състояние

След S02E02 най-силният работен модел е:

> **Juliette’s Silo е една unit в стандартизирана multi-Silo survival/control architecture. Cleaning increasingly appears to combine false lush perception, deliberately/systematically inferior standard sealing and an expected visible death; `THE ORDER` explicitly treats failed cleaning as a war-risk contingency. Bernard/IT also has a live exterior feed associated with Juliette, while Judge Meadows is read into at least `THE ORDER` and the tape secret.**

Ключови установени линии:

- cleaner lush view остава repeatable при Allison, Jane Carmody и Holston;
- public display normally показва barren exterior;
- S01E03 power-down показва lush state на самия public display;
- S01E04 показва normal night state;
- S01E05 показва systematic/time-dependent star-like movement на night display-а;
- observer в cafeteria не знае concept-а „stars“ и сам reconstruct-ва movement patterns;
- Silo има **144 levels** и Bernard заявява **10 112 current residents**;
- observed direct level anchors вече включват `8, 9, 12, 14, 17, 23, 26, 27, 29, 30, 50, 144`;
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
- observed level anchors now also include Level 26 and **Level 30**;
- Juliette’s mother used a homemade microscope/magnification device for independent medical investigation; restricted records show institutional attention to the activity;
- Juliette realizes mirror surveillance can explain discovery of her mother’s microscope without requiring father-as-informant;
- a priority Medical → Martha Walker message direct-confirms structured interdepartmental digital messaging;
- Mayor + Sims coordinate a trap and claim Juliette said she wanted to go out; she is arrested on that basis;
- Bernard/IT claims Judge Meadows is afraid of him; objective hierarchy remains unresolved;
- S01E08 ends with Juliette going over the railing during escape/evasion context;
- S01E09 resolves the immediate outcome: she survives the initial fall on an intermediate bridge at **Level 23**;
- a small illuminated object/device marked **`18`** is shown in Bernard/acting-mayor context; function unknown and no HDD-18 link is assumed;
- Juliette opens the known **`JANE CARMODY CLEANING`** file from the hard-drive evidence chain, bringing the alternate lush cleaning imagery directly into her own knowledge;
- S01E10 reveals that the lush cleaner/helmet view is a **false visual layer**; Juliette’s initial belief that the public display is lying is superseded by the direct reveal;
- barren exterior remains after the false layer drops and is therefore substantially real;
- Bernard recognizes that Juliette has understood the helmet deception and demonstrates privileged access/control over classified cleaning and surveillance information;
- Bernard can stop sensitive broadcast and order control-room personnel, including Sims, not to look/retain what they saw;
- Juliette’s suit uses different tape/material and she survives beyond the point Bernard/Sims expect a cleaner to die, strongly implicating suit sealing;
- the illuminated `18` object is directly shown to be a **physical key**; what it opens and whether it relates to HDD 18 remain unknown;
- wide exterior views reveal **multiple Silo installations** and a distant ruined/city-like skyline;
- Level 144/bottom contains large ventilation / air-handling machinery;
- official `THE SYNDROME` signage gives a partially legible symptom progression;
- Janitorial contains a structured day/level/time `ROTA` board.
- S02E01 directly places Juliette at and inside a **second Silo**, converting the multi-Silo model from exterior observation into direct exploration;
- opening historical sequence in that second Silo shows anti-Founder / anti-deception graffiti, a Sheriff-led assault/advance against IT, an airlock breach and a mass exit outside;
- present-day Juliette finds a large field of human remains around the second Silo hatch, strongly confirming a real lethal exterior hazard;
- Juliette experiences acute breathing distress while sealed in her suit inside the second Silo, then can breathe after opening/breaking the helmet; exact breathing technology remains unknown;
- current best-fit outside-hazard class is **airborne / atmosphere-borne exposure**; toxin/chemical/aerosol and pathogen remain competing possibilities;
- the second Silo contains the same concealed mirror-camera concept, strongly supporting standardized cross-Silo surveillance/control design;
- IT in the second Silo is a defended/secured strategic area with severed access, local lighting and a vault-like compartment;
- the second Silo is massively flooded to within a few levels below IT but is not completely electrically dead;
- at least one living person remains inside the secured IT compartment;
- young Juliette is shown visiting the excavation machine in her own Silo as a child;
- exact total Silo count and any relation `key 18 ↔ HDD 18 ↔ Silo 18` remain unresolved.
- S02E02 shows Bernard/IT receiving a **live Juliette-associated exterior video feed**; the signal is lost when she enters the second Silo;
- Bernard consults a distinct physical doctrine titled **`THE ORDER`**;
- `THE ORDER` explicitly states **`IN THE EVENT OF A FAILED CLEANING, PREPARE FOR WAR`**;
- Judge Meadows knows about `THE ORDER`, so this hidden doctrine is not Bernard's private secret;
- Bernard explicitly fears that the catastrophic fate of the second Silo could occur in his own Silo;
- Bernard and Meadows attribute Juliette's survival to replacement of the normal cleaning tape;
- Meadows says somebody would eventually figure the tape mechanism out and later demands the **good tape** before agreeing to go outside;
- the standard cleaning tape is therefore strongly supported as intentionally/systematically inferior, although contaminant ingress vs breathing-gas loss vs both remains unresolved;
- Bernard's Silo contains a secured/vault-like IT layer analogous to the second Silo's secured IT compartment;
- a distinct circled rebellion-context graffiti symbol/emblem appears; exact meaning remains unknown.

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
- [`docs/episodes/S01E08.md`](docs/episodes/S01E08.md) — episode record за S01E08.
- [`docs/episodes/S01E09.md`](docs/episodes/S01E09.md) — episode record за S01E09.
- [`docs/episodes/S01E10.md`](docs/episodes/S01E10.md) — episode record за S01E10.
- [`docs/episodes/S02E01.md`](docs/episodes/S02E01.md) — episode record за S02E01.
- [`docs/episodes/S02E02.md`](docs/episodes/S02E02.md) — episode record за S02E02.
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
- [`docs/evidence/S01E08-illicit-microscopy-and-mirror-surveillance.md`](docs/evidence/S01E08-illicit-microscopy-and-mirror-surveillance.md) — microscope, restricted record и revision на father-as-informant model.
- [`docs/evidence/S01E08-fabricated-cleaning-trigger.md`](docs/evidence/S01E08-fabricated-cleaning-trigger.md) — Mayor/Sims trap, disputed exit claim и arrest.
- [`docs/evidence/S01E08-bernard-judge-power.md`](docs/evidence/S01E08-bernard-judge-power.md) — Bernard’s claim за Judge Meadows и hidden hierarchy candidate.
- [`docs/evidence/S01E09-level23-escape.md`](docs/evidence/S01E09-level23-escape.md) — Level 23 bridge landing and escape outcome.
- [`docs/evidence/S01E09-number18-device.md`](docs/evidence/S01E09-number18-device.md) — illuminated object/device marked `18`, function unknown.
- [`docs/evidence/S01E09-jane-carmody-cleaning.md`](docs/evidence/S01E09-jane-carmody-cleaning.md) — Juliette opens the known Jane Carmody cleaning footage.
- [`docs/evidence/S01E10-cleaning-helmet-tape.md`](docs/evidence/S01E10-cleaning-helmet-tape.md) — false helmet layer, tape variation and cleaner-survival mechanism.
- [`docs/evidence/S01E10-bernard-compartmentalization.md`](docs/evidence/S01E10-bernard-compartmentalization.md) — Bernard privileged access/control and Sims compartmentalization.
- [`docs/evidence/S01E10-multiple-silos-exterior.md`](docs/evidence/S01E10-multiple-silos-exterior.md) — barren reality, multi-Silo field and distant skyline.
- [`docs/evidence/S01E10-key18.md`](docs/evidence/S01E10-key18.md) — physical key marked `18`.
- [`docs/evidence/S01E10-syndrome-level144-rota.md`](docs/evidence/S01E10-syndrome-level144-rota.md) — Syndrome sign, Level 144 infrastructure and Janitorial ROTA.
- [`docs/evidence/S02E01-other-silo-rebellion.md`](docs/evidence/S02E01-other-silo-rebellion.md) — second-Silo rebellion, IT assault and mass exit.
- [`docs/evidence/S02E01-outside-hazard-suit-breathing.md`](docs/evidence/S02E01-outside-hazard-suit-breathing.md) — outside hazard, suit seal and breathing-support model.
- [`docs/evidence/S02E01-cross-silo-surveillance-it.md`](docs/evidence/S02E01-cross-silo-surveillance-it.md) — repeated mirror-camera surveillance and IT standardization.
- [`docs/evidence/S02E01-power-flooding-survivor.md`](docs/evidence/S02E01-power-flooding-survivor.md) — residual power, flooding and surviving occupant.
- [`docs/evidence/S02E02-the-order-failed-cleaning.md`](docs/evidence/S02E02-the-order-failed-cleaning.md) — `THE ORDER`, failed-cleaning contingency and war-risk doctrine.
- [`docs/evidence/S02E02-live-cleaner-feed.md`](docs/evidence/S02E02-live-cleaner-feed.md) — live Juliette-associated exterior feed and transmission boundary.
- [`docs/evidence/S02E02-cleaning-tape-mechanism.md`](docs/evidence/S02E02-cleaning-tape-mechanism.md) — good/bad tape distinction and finite-protection model.
- [`docs/evidence/S02E02-it-vault-governance.md`](docs/evidence/S02E02-it-vault-governance.md) — repeated secured IT architecture and privileged read-in layer.
- [`docs/open-questions.md`](docs/open-questions.md) — активните въпроси за falsification / future testing.
- [`assets/S01E01/screenshots/`](assets/S01E01/screenshots/) — visual evidence от S01E01.
- [`assets/S01E02/screenshots/`](assets/S01E02/screenshots/) — selected visual evidence от S01E02.
- [`assets/S01E03/screenshots/`](assets/S01E03/screenshots/) — selected visual evidence от S01E03.
- [`assets/S01E04/screenshots/`](assets/S01E04/screenshots/) — selected visual evidence от S01E04.
- [`assets/S01E05/screenshots/`](assets/S01E05/screenshots/) — selected visual evidence от S01E05.
- [`assets/S01E06/screenshots/`](assets/S01E06/screenshots/) — selected visual evidence от S01E06.
- [`assets/S01E07/screenshots/`](assets/S01E07/screenshots/) — validated selected visual evidence от S01E07.
- [`assets/S01E07/MANIFEST.md`](assets/S01E07/MANIFEST.md) — S01E07 visual processing/selection manifest.
- [`assets/S01E08/screenshots/`](assets/S01E08/screenshots/) — validated selected visual evidence от S01E08.
- [`assets/S01E08/MANIFEST.md`](assets/S01E08/MANIFEST.md) — S01E08 visual processing/selection manifest.
- [`assets/S01E09/screenshots/`](assets/S01E09/screenshots/) — validated selected visual evidence от S01E09.
- [`assets/S01E09/MANIFEST.md`](assets/S01E09/MANIFEST.md) — S01E09 visual processing/selection manifest.
- [`assets/S01E10/screenshots/`](assets/S01E10/screenshots/) — validated selected visual evidence от S01E10.
- [`assets/S01E10/MANIFEST.md`](assets/S01E10/MANIFEST.md) — S01E10 visual processing/selection manifest.
- [`assets/S02E01/screenshots/`](assets/S02E01/screenshots/) — validated selected visual evidence от S02E01.
- [`assets/S02E01/MANIFEST.md`](assets/S02E01/MANIFEST.md) — S02E01 visual processing/selection manifest.
- [`assets/S02E02/screenshots/`](assets/S02E02/screenshots/) — validated selected visual evidence от S02E02.
- [`assets/S02E02/MANIFEST.md`](assets/S02E02/MANIFEST.md) — S02E02 visual processing/selection manifest.
- [`assets/S02E01/screenshots/`](assets/S02E01/screenshots/) — validated selected visual evidence от S02E01.
- [`assets/S02E01/MANIFEST.md`](assets/S02E01/MANIFEST.md) — S02E01 visual processing/selection manifest.

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

### Допълнително правило след S01E08

**Character belief can be superseded by a newly observed mechanism; institutional testimony can itself be the coercive mechanism.**

- Juliette’s earlier belief that her father exposed the microscope is no longer required once mirror surveillance is known and she herself connects the two.
- The Mayor/Sims “she wants to go out” claim is tracked separately from what Juliette actually said; downstream arrest does not retroactively make the claim true.

### Допълнително правило след S01E09

**Evidence becoming known to a character is tracked separately from evidence already known to the viewer/project.**

The Jane Carmody cleaning footage was already direct visual evidence in S01E01. S01E09 is important because Juliette herself now accesses that same evidence; it does not make the lush image newly true or resolve whether it is real vs manipulated.

### Допълнително правило след S01E10

**Character conclusions remain separate from direct system reveals.** Juliette initially concludes that the public display is the lie because her helmet shows lush imagery; S01E10 then directly reveals the helmet imagery itself as false. The ledger therefore preserves her statement as a character inference and the later reveal as higher-grade evidence.

### Допълнително правило след S02E01

**Cross-Silo repetition strengthens standardization hypotheses, not automatic central-control conclusions.** When the same architecture appears in a second Silo — mirror cameras, IT, airlock, agriculture — we may infer common design/doctrine more strongly, but we do not automatically conclude one live central authority controls every Silo.

**Superseded inferences remain in history.** E188 preserves the initial mistaken Engineering/generator-target interpretation and marks it superseded after later scene evidence identifies IT as the actual attacked/defended location.

### Допълнително правило след S02E02

**Privileged doctrine, insider interpretation and direct mechanism remain separate evidence classes.** `THE ORDER` heading is direct institutional evidence; Bernard/Meadows tape explanations are insider testimony; exact engineering mechanism remains unresolved until directly established.

**Repeated cross-Silo secured architecture supports standardization, not identical contents.** Similar IT vault-like compartments in two Silos strengthen H38 without assuming they contain the same systems, people or doctrine.

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

## Текущ модел за външния свят

След S02E02 основната visual ambiguity остава разрешена, а cleaner survival/control model-ът е substantially stronger:

1. **Lush cleaner view is false** — helmet-ът показва manipulated / overlay-like visual layer.
2. **Barren exterior is substantially real** — след отпадането на false layer Juliette вижда devastated terrain.
3. **Multiple Silo installations exist** в surrounding landscape.
4. В далечината се вижда **ruined / city-like skyline**, но identity/location не са установени.
5. Juliette directly reaches and enters a **second Silo**.
6. A large mass-remains field around that Silo confirms a real lethal exterior hazard under observed conditions.
7. Current best-fit hazard class is airborne / atmosphere-borne; exact toxin/pathogen/particulate mechanism remains unresolved.
8. Suit sealing and breathing-support integrity materially affect survival.
9. Insider dialogue strongly ties Juliette's survival to replacement of the normal cleaning tape with a better seal.
10. Bernard/IT receives live exterior video associated with Juliette while she is outside.

Все още са unresolved exact helmet-rendering technology, exact outside lethal agent, exact suit leak pathway, exact source/format of the live cleaner feed, total Silo count/status, any current central authority, Silo numbering and identity-то на distant skyline.

## Текущ architectural model

```text
EXTERIOR
  ├─ barren terrain
  ├─ multiple neighboring Silo installations
  └─ distant ruined / city-like skyline
        │
        ▼
SURFACE / CLEANING EXIT
        │
        ▼
LEVEL 1 / UP-TOP ?
        │
        ├─ Sheriff's Department / holding
        ├─ Cell 3
        └─ cleaning airlock opposite Cell 3
        │
        ▼
LEVEL 8 → 9 → 12 → ~14 JUDICIAL → 17 → 23 → 26 → 27 → 29 → 30
        │
        ▼
LEVEL 50 / MIDS
        │
        ▼
DOWN-DEEP
        │
        ▼
LEVEL 144 / BOTTOM
        ├─ major ventilation / air-handling infrastructure
        └─ relation to lower hidden construction layer ?
        │
        ▼
PACT-FORBIDDEN PRE-REBELLION TUNNEL / LOWER LAYER ?
        │
        ▼
SUB-SILO CONSTRUCTION CAVITY
        ├─ excavation machine
        ├─ George cache / PEZ trail
        └─ flooded bottom
               │
               └─ reported short tunnel + door ?
```

Question marks означават strong spatial inference или unresolved relation, не single-frame direct confirmation.

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
episode/S01E09-analysis
episode/S01E10-analysis
episode/S02E01-analysis
episode/S02E02-analysis
hypothesis/<name>
model/<name>
methodology/<change>
```

Git history е част от разследването: трябва да можем да видим кога е възникнала една theory, кой evidence я е укрепил, кой я е отслабил и кога е била refactor-ната или отхвърлена.

---

**Следваща knowledge boundary:** `S02E03`
