# Проект SILO — reverse engineering на Engineered Survival System

Дневник за систематичен, evidence-driven и spoiler-disciplined анализ на телевизионния сериал **Silo**.

Целта е да третираме света на сериала като **черна кутия**: наблюдаваме поведението на системата, извличаме възможни правила, строим competing hypotheses и ги променяме или отхвърляме, когато нови епизоди дадат по-добър evidence.

> **След S02E10 / края на Season 2 `the safeguard` вече е физически установена whole-Silo poison system: external pipe влиза при Level 14 и може да убие local population, а Silo 17 testimony показва, че path-ът може да бъде блокиран. Финалът също отваря direct pre-Silo Washington timeline с radiation screening, Georgia congressman, disputed radiological-attack narrative и PEZ provenance clue.**

## Език на проекта

Основният език на repo-то е **български**.

Всички обяснителни текстове, анализи, conclusions, въпроси и описания се пишат на български. Утвърдени технически термини могат да останат на английски, когато това прави модела по-точен или по-четим — например `evidence`, `confidence`, `hypothesis`, `knowledge boundary`, `direct observation`, `institutional claim`, `visual pipeline`, `feed`, `overlay`, `falsification`, `branch` и `PR`.

Имената на файлове, branch-ове, code identifiers и оригинални UI/file labels от сериала не се превеждат задължително.

### Задължително езиково правило

**Обяснителният prose в repo-то се пише на български.**

Английски могат да останат:
- утвърдени project/technical terms като `evidence`, `confidence`, `hypothesis`, `knowledge boundary`, `direct observation`, `institutional claim`, `feed`, `overlay`, `branch`, `PR`;
- точни цитати от сериала;
- оригинални UI/document labels като `THE ORDER`, `DIRECT MESSAGING`, `SERVER ROOM`, `Legacy`;
- filenames, paths, branch names и code identifiers;
- собствени имена.

**Цели английски обяснителни изречения не се използват**, освен когато са точен цитат или оригинален текст от UI/document evidence.

## Knowledge boundary

**Текуща граница на знанието:** **S02E10 — Season 2 finished**

**Статус на гледане:** **Сезон 2 — завършен**

Не се използва никаква информация след S02E10, книги, wiki, interviews, бъдещи synopses, leaks или retrospective explanations.

## Текущо състояние

След S02E10 / края на Season 2 най-силният работен модел е:

> **Silo system трябва да се моделира като layered survival/control architecture: public habitation → privileged IT/Legacy continuity → hidden lower contact/control → externally supplied safeguard poison path. Outside hazard остава отделен physical threat. Direct pre-Silo Washington scene вече добавя първия contemporaneous origin-era political/security context.**

Ключови установени линии:

- cleaner lush view остава repeatable при Allison, Jane Carmody и Holston;
- public display normally показва barren exterior;
- S01E03 power-down показва lush state на самия public display;
- S01E04 показва normal night state;
- S01E05 показва systematic/time-dependent star-like movement на night display-а;
- observer в cafeteria не знае concept-а „stars“ и сам reconstruct-ва movement patterns;
- Silo има **144 levels** и Bernard заявява **10 112 current residents**;
- observed direct level anchors вече включват `8, 9, 12, 14, 17, 23, 26, 27, 29, 30, 50, 55, 119, 120, 123, 144`;
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
- Flamekeepers са описани като група, съхраняваща историята/relics; точната им връзка с Rebellion остава неустановена;
- historical testimony въвежда memory suppression чрез водата преди/около Rebellion-era;
- бащата на Juliette лично признава измамата с премахването на implant-а, потвърждавайки covert reproductive-control mechanism;
- Juliette и George са свързани чрез своите Flamekeeper майки и intergenerational preservation network;
- наблюдаваните level anchors вече включват и Level 26 и **Level 30**;
- майката на Juliette използва homemade microscope/magnification device за независимо медицинско изследване; restricted records показват институционално внимание към тази дейност;
- Juliette осъзнава, че mirror surveillance може да обясни откриването на микроскопа на майка ѝ, без да е нужен моделът father-as-informant;
- priority съобщение Medical → Martha Walker директно потвърждава structured interdepartmental digital messaging;
- Mayor + Sims координират капан и твърдят, че Juliette е казала, че иска да излезе навън; тя е арестувана на тази основа;
- Bernard/IT твърди, че Judge Meadows се страхува от него; обективната hierarchy остава unresolved;
- S01E08 завършва с Juliette, която преминава през парапета в контекст на escape/evasion;
- S01E09 разрешава непосредствения outcome: тя оцелява след първоначалното падане върху междинен bridge на **Level 23**;
- показан е малък осветен object/device с маркировка **`18`** в контекст с Bernard/acting mayor; функцията е неизвестна и не се приема автоматична връзка с HDD 18;
- Juliette отваря познатия файл **`JANE CARMODY CLEANING`** от hard-drive evidence chain, което прави alternate lush cleaning imagery част от собственото ѝ knowledge;
- S01E10 разкрива, че lush cleaner/helmet view е **false visual layer**; първоначалното убеждение на Juliette, че public display лъже, е superseded от директното разкритие;
- barren exterior остава видим след отпадането на false layer и следователно е в значителна степен реален;
- Bernard разпознава, че Juliette е разбрала helmet deception, и демонстрира privileged access/control върху classified cleaning и surveillance информация;
- Bernard може да спре sensitive broadcast и да нареди на control-room personnel, включително Sims, да не гледат/запазват видяното;
- suit-ът на Juliette използва различен tape/material и тя оцелява отвъд момента, в който Bernard/Sims очакват cleaner да умре, което силно implicate-ва suit sealing;
- осветеният object `18` е директно показан като **physical key**; какво отключва и дали е свързан с HDD 18 остават неизвестни;
- wide exterior кадрите разкриват **multiple Silo installations** и далечен ruined/city-like skyline;
- Level 144/bottom съдържа голяма ventilation / air-handling machinery;
- официалната табела `THE SYNDROME` дава частично четима symptom progression;
- Janitorial съдържа structured day/level/time `ROTA` board.
- S02E01 директно поставя Juliette при и вътре във **втори Silo**, превръщайки multi-Silo model от exterior observation в direct exploration;
- opening historical sequence във втория Silo показва anti-Founder / anti-deception graffiti, Sheriff-led assault/advance срещу IT, airlock breach и mass exit навън;
- в present-day сцените Juliette намира голямо поле от човешки останки около hatch-а на втория Silo, което силно потвърждава real lethal exterior hazard;
- Juliette изпитва acute breathing distress, докато е sealed в suit-а си вътре във втория Silo, а след отваряне/разбиване на helmet-а отново може да диша; exact breathing technology остава неизвестна;
- текущият best-fit клас за outside hazard е **airborne / atmosphere-borne exposure**; toxin/chemical/aerosol и pathogen остават competing possibilities;
- вторият Silo съдържа същия concealed mirror-camera concept, което силно подкрепя standardized cross-Silo surveillance/control design;
- IT във втория Silo е defended/secured strategic area със severed access, local lighting и vault-like compartment;
- вторият Silo е масивно наводнен до няколко нива под IT, но не е напълно electrically dead;
- поне един жив човек остава вътре в secured IT compartment;
- показана е младата Juliette, която като дете посещава excavation machine в своя Silo;
- exact total Silo count и всяка връзка `key 18 ↔ HDD 18 ↔ Silo 18` остават unresolved.
- S02E02 показва как Bernard/IT получава **live Juliette-associated exterior video feed**; сигналът се губи, когато тя влиза във втория Silo;
- Bernard използва отделна физическа doctrine, озаглавена **`THE ORDER`**;
- `THE ORDER` изрично гласи **`IN THE EVENT OF A FAILED CLEANING, PREPARE FOR WAR`**;
- Judge Meadows знае за `THE ORDER`, следователно тази hidden doctrine не е лична тайна на Bernard;
- Bernard изрично се страхува, че катастрофалната съдба на втория Silo може да се повтори и в неговия;
- Bernard и Meadows приписват оцеляването на Juliette на замяната на normal cleaning tape;
- Meadows казва, че някой рано или късно ще разбере tape mechanism, а по-късно изисква **good tape**, преди да се съгласи да излезе навън;
- standard cleaning tape следователно е силно подкрепен като умишлено/системно inferior, макар contaminant ingress vs breathing-gas loss vs both да остава unresolved;
- Silo на Bernard съдържа secured/vault-like IT layer, аналогичен на secured IT compartment във втория Silo;
- появява се distinct circled rebellion-context graffiti symbol/emblem; exact meaning остава неизвестно.
- survivor testimony в S02E03 идентифицира другата инсталация като **Silo 17** и заявява **50 Silos**; S02E09 Quinn material независимо казва, че Founders са построили **50**, но Bernard уточнява, че реалният брой е **51**; причината за discrepancy остава unresolved, а оригиналният Silo на Juliette е силно identified/inferred като **Silo 18**;
- отказът на Ron да clean-не, съобщението `LIES` и изчезването му от view са последвани от вътрешно `LIES` съобщение и rebellion в Silo 17;
- survivor-ът от Silo 17 казва, че хората по-късно излизат, защото не виждат Ron да умира и заключават, че exterior е безопасен; това силно corroborate-ва visible cleaner death като population deterrence;
- жителите на Silo 17 са описани като оцелели навън, докато dust/poison временно се разсейва, след което умират при завръщането на hazard-а; real exterior lethality и ordinary cleaner timing следователно са distinct mechanisms;
- IT compartment-ът в Silo 17 е изрично наречен **vault**; Russell поставя survivor-а вътре и му нарежда да не допуска никого;
- physical key `18` на Bernard дава достъп до **SERVER ROOM**, а vault-ът е вътре в него;
- Bernard казва, че Jane Carmody cleaning recording е на около **200 години**, и е знаел, че Silo 17 е "dead", много преди текущата криза;
- Sims изрично предлага medication, за да може човек да **forget**, което независимо corroborate-ва pharmacological memory-suppression capability;
- `CODE SILO ORANGE` директно инструктира medical staff да не премахва birth control, като гарантира, че patient вярва, че е премахнат;
- същият medical record използва `DOB 09/13/116 A.R.`, което налага chronology на H15 да бъде weakened/refactored, а не мълчаливо запазена;
- Juliette изрично идентифицира lush cleaning view като behavioral trigger за clean-ването и разпознава измамата по повторения Jane Carmody visual pattern, включително същото движение на летящите същества;
- Judge Meadows излага теория, че The Syndrome може да е реакция към живота в Silo, а не primary physiological disease.
- S02E04 разкрива, че `THE ORDER` инструктира leadership да обвинява **Mechanical** при rebellion/crisis;
- historical markings в Mechanical се интерпретират като знак, че Mechanical многократно е бил обвиняван независимо откъде реално започва unrest;
- текущото best explanation за избора на Mechanical е контролът му върху generator/critical infrastructure, но това остава hypothesis;
- мините осигуряват metal, използван в Silo, а опасната/нежелана mining работа се изпълнява частично чрез **penal labor system**;
- survivor-ът от Silo 17 е бил дете по време на rebellion и е бил поставен/заключен в IT vault още от детството, което strengthen-ва continuity/survival-refuge interpretation;
- Level **119** е директно наблюдаван като нов spatial anchor;
- Bernard poisons Judge Meadows;
- Meadows пита за hard drive, свързан със **Salvador Quinn**, описан като Head of IT по време на Rebellion преди приблизително 140 години;
- Quinn оставя писмо, което е поне частично encoded;
- Meadows напуска shadow path на Bernard преди около 25 години след четиридневно изчезване;
- Bernard демонстрира immersive headset, показващ Monteverde cloud forest, 2018, и обяснява, че работи подобно на cleaner-helmet visual technology;
- Bernard дава този headset на Meadows преди смъртта ѝ;
- Bernard инсценира пристигането на представители на Mechanical на мястото на смъртта на Meadows, за да може Mechanical да бъде обвинен и public anger да бъде пренасочен към тях;
- Bernard твърди, че impeachment protests са го принудили да действа, и казва, че Sims стои зад натиска;
- Sims активно насочва public sentiment срещу Mechanical, демонстрирайки meaningful independent political/operational leverage;
- S02E04 завършва с large-scale population movement по време на escalating unrest.
- S02E05 показва как Bernard отстранява Sims като Head of Security, изрично му отказва ролята `shadow` и го назначава за Judge;
- това разделя public Judicial office от privileged IT succession/read-in path на Bernard, без да доказва, че всеки Judge е просто puppet;
- survivor-ът от Silo 17 казва, че IT има собствен independent power supply от external/outside source спрямо normal generator path;
- pump на Level 144 е унищожена по време на rebellion в Silo 17, за да бъде наводнен Mechanical; покачващата се вода в крайна сметка изключва main generator и продължава да се покачва;
- survivor-ът иска Juliette да ремонтира pump и да я захрани от IT, което предполага, че continuity power може потенциално да поддържа избрани non-IT recovery loads;
- Level 26 отново е директно показан като repeated spatial anchor;
- директно е показано голямо multilevel landscaped common/circulation area;
- новооткрита Silo schematic показва маркирани линии, свързани в scene context едновременно с IT и Judicial; line type/source остават unresolved;
- в архива е намерено scanned handwritten писмо на Salvador Quinn;
- encoded/ciphered material е конкретно в края на писмото на Quinn, което refine-ва по-ранното описание 'partly encoded'.
- S02E06 директно показва Sheriff Department `DIRECT MESSAGING` interface с departmental и named senders;
- директно е показан two-way person-to-person digital conversation;
- това weaken-ва всеки модел, според който couriers съществуват просто защото electronic messaging не съществува;
- control room получава routed written field intelligence за движение и оборудване на въоръжена група;
- exact source device/input path, използван от field informants, остава unresolved;
- Bernard/IT може да прекъсва всички radio communications в Silo, установявайки centralized communications-control capability;
- най-силният communication model вече съдържа поне три паралелни tiers: physical couriers, institutional digital messaging и centrally controllable radio;
- Level 55 и Level 120 стават нови direct spatial anchors.
- S02E07 разкрива residential/living compartments вътре в secured IT vault;
- protected vault component, наречен `Legacy`, е идентифициран като library / knowledge archive;
- `Legacy` дава конкретен механизъм privileged institutional memory да оцелява през generations/succession;
- Bernard заявява, че Silo е построен преди **352 години**;
- комбинирано с ~140-years-ago Rebellion anchor, construction е приблизително **212 години преди Rebellion**;
- handwritten leaflet гласи `I.T. Lies to us`, `Mechanical wants THE TRUTH`, пита какво се е случило с Juliette, как наистина е умряла Meadows и какво крие IT;
- leaflet-ът установява circulating anti-IT counter-narrative, но не и неговия author/distributor;
- по време на general Silo 18 blackout IT остава видимо powered и жителите изрично забелязват изключението;
- continuity power следователно е независимо демонстрирано поне в Silos 17 и 18, докато exact source equivalence остава unresolved.
- S02E08 разкрива privileged alternative history на Bernard: Quinn не се е провалил по време на Rebellion, а умишлено е reset-нал public historical continuity;
- Bernard казва, че pre-Quinn rebellions са се повтаряли приблизително на всеки 20 години и всеки е застрашавал целия Silo;
- Quinn премахва public server access, конфискува книги и позволява/причинява историческата загуба да бъде приписана на rebels;
- Bernard казва, че Quinn поставя memory-suppressing chemical/drug във водата; chronic exposure в течение на седмици, месеци и години кара спомените да избледняват;
- това независимо corroborate-ва по-ранното Flamekeeper water-memory testimony и силно strengthens pharmacological memory-suppression model;
- Bernard приписва приблизително 140 години мир на intervention-а на Quinn, докато тази causal diagnosis остава privileged interpretation, а не independent proof;
- по-ранното Quinn investigation на Meadows вече е свързано с роднините на Quinn и оцелели books/materials;
- старо копие със заглавие `The Pact Between the Founders` носи ръкописното име `Salvador Quinn`; association е direct, но authorship/Founder status не са;
- декодираното съобщение на Quinn гласи: `If you've gotten this far, you already know the game is rigged.` („Ако си стигнал дотук, вече знаеш, че играта е нагласена.“);
- Judge Sims получава лично съобщение от R. Ahundsen, в което се споменават погребение и `little apple tree`; голям orchard дава plausible literal referent, но coded intent остава unresolved;
- Silo 17 директно съдържа множество живи обитатели, не само познатия досега IT-vault survivor.
- S02E09 показва организирана additional-survivor group в Silo 17; group-ът нарича IT-vault survivor-а „the killer“ и го използва като leverage за food;
- Silo 17 vault директно съдържа large books/archive/scientific-knowledge environment, функционално аналогична на `Legacy` в Silo 18, без official `Legacy` label да е confirmed;
- decoded Quinn material казва: `The founders didn't build a single silo. They built fifty.` и `And they created the safeguard.`;
- Bernard отделно заявява, че real count е **51**, а Heads of IT и shadows знаят за другите Silos;
- Quinn оставя последователни указания за физическа проверка: `go to the very bottom` („слез до самото дъно“) → `find the tunnel` („намери тунела“) → `you will get confirmation there` („там ще получиш потвърждение“);
- observed bottom zone на Silo 18 е shallow/passable, а real tunnel/opening действително е намерен;
- в tunnel/lower zone active unknown interlocutor/system води context-aware two-way conversation с Lukas;
- lower contact казва, че преди Lukas само **Salvador Quinn, Mary Meadows и George Wilkins** са достигали до тази точка;
- Bernard не е сред previous visitors; това доказва non-visitation, не automatic ignorance;
- Lukas е предупреден, че disclosure на видяното/наученото там ще доведе до activation на `the safeguard`; exact mechanism/controller/effect остават unresolved в S02E09;
- shadow-ът на Bernard спекулира за hidden pumps под known bottom, неизвестни на Mechanical; това остава speculation;
- digital coercive message изисква camera-on/no-leave compliance и използва wife като leverage; sender/recipient identity не се извежда само от screenshot-а.

- S02E10 direct-confirm-ва Level 123 и показва stair sabotage, което operationally split-ва Bernard's forces;
- `the safeguard` вече е physical poison-delivery pipe, capable of whole-Silo kill;
- Silo 17 survivor-ът казва, че parents са успели да block-нат safeguard-а;
- safeguard supply идва отвън и влиза при Level 14;
- това refactor-ва model-а: outside hazard и safeguard са distinct lethal mechanisms;
- Juliette се връща в Silo 18 и показва `not safe / do not come out`;
- Bernard лично я посреща при airlock-а;
- Juliette казва, че **може би знае как да спре safeguard-а**;
- коригираната sequence е: stopping claim → Juliette + Bernard enter → burner/flame cycle;
- финалът показва direct pre-Silo Washington scene;
- radiation screening е routine enough да се използва пред bar;
- central character е Congressman from Georgia's 15th congressional district;
- alleged radiological attack е attributed to Iran, но dialogue-ът поставя под въпрос дали attack изобщо е имало;
- possible retaliatory strike срещу Iran е част от политическия разговор, не established executed action;
- Congressman-ът подарява yellow-duck PEZ dispenser; това е strong candidate provenance bridge към earlier Silo-era yellow-plastic/blue-handle relic, без exact same-object continuity да е proven.

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
- [`docs/episodes/S02E03.md`](docs/episodes/S02E03.md) — episode record за S02E03.
- [`docs/episodes/S02E04.md`](docs/episodes/S02E04.md) — episode record за S02E04.
- [`docs/episodes/S02E05.md`](docs/episodes/S02E05.md) — episode record за S02E05.
- [`docs/episodes/S02E06.md`](docs/episodes/S02E06.md) — episode record за S02E06.
- [`docs/episodes/S02E07.md`](docs/episodes/S02E07.md) — episode record за S02E07.
- [`docs/episodes/S02E08.md`](docs/episodes/S02E08.md) — episode record за S02E08.
- [`docs/episodes/S02E09.md`](docs/episodes/S02E09.md) — episode record за S02E09.
- [`docs/episodes/S02E10.md`](docs/episodes/S02E10.md) — Season 2 finale record за S02E10.
- [`docs/evidence-ledger.md`](docs/evidence-ledger.md) — evidence регистър с confidence и epistemic class.
- [`docs/evidence/S01E01-exterior-visual-contradiction.md`](docs/evidence/S01E01-exterior-visual-contradiction.md) — focused exterior evidence след S01E01.
- [`docs/evidence/S01E02-holston-visual-split.md`](docs/evidence/S01E02-holston-visual-split.md) — simultaneous cleaner/public visual split при Holston.
- [`docs/evidence/S01E02-sub-silo-construction-layer.md`](docs/evidence/S01E02-sub-silo-construction-layer.md) — hidden construction layer под Silo.
- [`docs/evidence/S01E03-public-display-powerdown-flash.md`](docs/evidence/S01E03-public-display-powerdown-flash.md) — lush state на public display при power-down.
- [`docs/evidence/S01E04-sheriff-succession-and-control.md`](docs/evidence/S01E04-sheriff-succession-and-control.md) — Judicial/IT opposition и Sheriff succession conflict.
- [`docs/evidence/S01E05-surveillance-trumbull-coverup.md`](docs/evidence/S01E05-surveillance-trumbull-coverup.md) — surveillance, framing, Trumbull и false suicide narrative.
- [`docs/evidence/S01E05-celestial-observation.md`](docs/evidence/S01E05-celestial-observation.md) — star-like temporal behavior и lost astronomical knowledge.
- [`docs/evidence/S01E05-pact-capability-restrictions.md`](docs/evidence/S01E05-pact-capability-restrictions.md) — mechanized-transport и magnification restrictions.
- [`docs/evidence/S01E06-centralized-surveillance.md`](docs/evidence/S01E06-centralized-surveillance.md) — директно потвърдено centralized internal surveillance.
- [`docs/evidence/S01E06-relic-database-pre-silo.md`](docs/evidence/S01E06-relic-database-pre-silo.md) — PEZ lookup, Judicial relic DB и preserved pre-Silo knowledge.
- [`docs/evidence/S01E06-georgia-relic.md`](docs/evidence/S01E06-georgia-relic.md) — pre-Silo geographic clue за Georgia, USA.
- [`docs/evidence/S01E07-surveillance-command-and-mirrors.md`](docs/evidence/S01E07-surveillance-command-and-mirrors.md) — Sims command, mirror cameras и concealed surveillance architecture.
- [`docs/evidence/S01E07-flamekeepers-memory-erasure.md`](docs/evidence/S01E07-flamekeepers-memory-erasure.md) — Flamekeepers, relic preservation и water-memory claim.
- [`docs/evidence/S01E07-reproductive-control.md`](docs/evidence/S01E07-reproductive-control.md) — doctor confession и reproductive-control mechanism.
- [`docs/evidence/S01E07-flamekeeper-family-network.md`](docs/evidence/S01E07-flamekeeper-family-network.md) — intergenerational Flamekeeper връзка между Juliette и George.
- [`docs/evidence/S01E08-illicit-microscopy-and-mirror-surveillance.md`](docs/evidence/S01E08-illicit-microscopy-and-mirror-surveillance.md) — microscope, restricted record и revision на father-as-informant model.
- [`docs/evidence/S01E08-fabricated-cleaning-trigger.md`](docs/evidence/S01E08-fabricated-cleaning-trigger.md) — Mayor/Sims trap, disputed exit claim и arrest.
- [`docs/evidence/S01E08-bernard-judge-power.md`](docs/evidence/S01E08-bernard-judge-power.md) — Bernard’s claim за Judge Meadows и hidden hierarchy candidate.
- [`docs/evidence/S01E09-level23-escape.md`](docs/evidence/S01E09-level23-escape.md) — приземяване върху bridge на Level 23 и резултат от escape-а.
- [`docs/evidence/S01E09-number18-device.md`](docs/evidence/S01E09-number18-device.md) — illuminated object/device с маркировка `18`, с неизвестна функция.
- [`docs/evidence/S01E09-jane-carmody-cleaning.md`](docs/evidence/S01E09-jane-carmody-cleaning.md) — Juliette отваря познатия Jane Carmody cleaning footage.
- [`docs/evidence/S01E10-cleaning-helmet-tape.md`](docs/evidence/S01E10-cleaning-helmet-tape.md) — false helmet layer, tape variation и cleaner-survival mechanism.
- [`docs/evidence/S01E10-bernard-compartmentalization.md`](docs/evidence/S01E10-bernard-compartmentalization.md) — privileged access/control на Bernard и compartmentalization на Sims.
- [`docs/evidence/S01E10-multiple-silos-exterior.md`](docs/evidence/S01E10-multiple-silos-exterior.md) — barren reality, multi-Silo field и distant skyline.
- [`docs/evidence/S01E10-key18.md`](docs/evidence/S01E10-key18.md) — physical key с маркировка `18`.
- [`docs/evidence/S01E10-syndrome-level144-rota.md`](docs/evidence/S01E10-syndrome-level144-rota.md) — Syndrome sign, Level 144 infrastructure и Janitorial ROTA.
- [`docs/evidence/S02E01-other-silo-rebellion.md`](docs/evidence/S02E01-other-silo-rebellion.md) — rebellion във втория Silo, IT assault и mass exit.
- [`docs/evidence/S02E01-outside-hazard-suit-breathing.md`](docs/evidence/S02E01-outside-hazard-suit-breathing.md) — outside hazard, suit seal и breathing-support model.
- [`docs/evidence/S02E01-cross-silo-surveillance-it.md`](docs/evidence/S02E01-cross-silo-surveillance-it.md) — повторено mirror-camera surveillance и IT standardization.
- [`docs/evidence/S02E01-power-flooding-survivor.md`](docs/evidence/S02E01-power-flooding-survivor.md) — residual power, flooding и surviving occupant.
- [`docs/evidence/S02E02-the-order-failed-cleaning.md`](docs/evidence/S02E02-the-order-failed-cleaning.md) — `THE ORDER`, failed-cleaning contingency и war-risk doctrine.
- [`docs/evidence/S02E02-live-cleaner-feed.md`](docs/evidence/S02E02-live-cleaner-feed.md) — live exterior feed, свързан с Juliette, и transmission boundary.
- [`docs/evidence/S02E02-cleaning-tape-mechanism.md`](docs/evidence/S02E02-cleaning-tape-mechanism.md) — разграничение good/bad tape и finite-protection model.
- [`docs/evidence/S02E02-it-vault-governance.md`](docs/evidence/S02E02-it-vault-governance.md) — повторена secured IT architecture и privileged read-in layer.
- [`docs/evidence/S02E03-silo17-failed-cleaning-rebellion.md`](docs/evidence/S02E03-silo17-failed-cleaning-rebellion.md) — failed cleaning в Silo 17, visible-death deterrence и rebellion cascade.
- [`docs/evidence/S02E03-outside-hazard-cleaner-death.md`](docs/evidence/S02E03-outside-hazard-cleaner-death.md) — mobile outside hazard спрямо ordinary cleaner death timing.
- [`docs/evidence/S02E03-memory-suppression.md`](docs/evidence/S02E03-memory-suppression.md) — текуща targeted pharmacological forgetting capability.
- [`docs/evidence/S02E03-key18-server-room-vault.md`](docs/evidence/S02E03-key18-server-room-vault.md) — `key 18 → SERVER ROOM → vault` и protected-vault evidence от Silo 17.
- [`docs/evidence/S02E03-silo-orange-chronology.md`](docs/evidence/S02E03-silo-orange-chronology.md) — formal reproductive-control protocol, `116 A.R.` и chronology correction.
- [`docs/evidence/S02E03-cleaner-perception-pattern.md`](docs/evidence/S02E03-cleaner-perception-pattern.md) — повторен Jane visual pattern, cleaning trigger и изгубен natural-world vocabulary.
- [`docs/evidence/S02E04-mechanical-scapegoating.md`](docs/evidence/S02E04-mechanical-scapegoating.md) — `THE ORDER`, повторено обвиняване на Mechanical и crisis scapegoating.
- [`docs/evidence/S02E04-mines-penal-labor.md`](docs/evidence/S02E04-mines-penal-labor.md) — metal extraction и penal labor system.
- [`docs/evidence/S02E04-salvador-quinn-meadows.md`](docs/evidence/S02E04-salvador-quinn-meadows.md) — Salvador Quinn, encoded letter и четиридневното изчезване на Meadows.
- [`docs/evidence/S02E04-vr-cleaner-technology.md`](docs/evidence/S02E04-vr-cleaner-technology.md) — immersive Monteverde headset и връзката с cleaner-helmet technology.
- [`docs/evidence/S02E04-meadows-framing-sims.md`](docs/evidence/S02E04-meadows-framing-sims.md) — убийството на Meadows, framing на Mechanical и натискът на Sims.
- [`docs/evidence/S02E04-silo17-child-vault.md`](docs/evidence/S02E04-silo17-child-vault.md) — survivor-ът от Silo 17 като дете и vault continuity-refuge model.
- [`docs/evidence/S02E05-sims-judge-shadow.md`](docs/evidence/S02E05-sims-judge-shadow.md) — reassignment на Sims, Judge office и отделен shadow succession path.
- [`docs/evidence/S02E05-silo17-power-flooding-recovery.md`](docs/evidence/S02E05-silo17-power-flooding-recovery.md) — independent IT power, саботаж на Level 144 pump, flooding и recovery plan.
- [`docs/evidence/S02E05-it-judicial-infrastructure-map.md`](docs/evidence/S02E05-it-judicial-infrastructure-map.md) — schematic lines, свързани с IT/Judicial, и hidden-backbone hypothesis.
- [`docs/evidence/S02E05-salvador-quinn-letter.md`](docs/evidence/S02E05-salvador-quinn-letter.md) — сканирано Quinn letter и encoded final payload.
- [`docs/evidence/S02E06-institutional-messaging.md`](docs/evidence/S02E06-institutional-messaging.md) — direct messaging, coexistence с courier и layered communication access.
- [`docs/evidence/S02E06-control-room-humint.md`](docs/evidence/S02E06-control-room-humint.md) — routed field/HUMINT reporting към control-room operational picture.
- [`docs/evidence/S02E06-radio-communications-control.md`](docs/evidence/S02E06-radio-communications-control.md) — Silo-wide radio cutoff capability на Bernard/IT.
- [`docs/evidence/S02E07-legacy-vault.md`](docs/evidence/S02E07-legacy-vault.md) — vault habitation, Legacy library и institutional-memory mechanism.
- [`docs/evidence/S02E07-352-year-chronology.md`](docs/evidence/S02E07-352-year-chronology.md) — 352-годишна възраст от construction и pre-Rebellion chronology refactor.
- [`docs/evidence/S02E07-anti-it-counter-narrative.md`](docs/evidence/S02E07-anti-it-counter-narrative.md) — handwritten anti-IT leaflet и competing crisis narrative.
- [`docs/evidence/S02E07-silo18-continuity-power.md`](docs/evidence/S02E07-silo18-continuity-power.md) — blackout-resilient IT power в Silo 18 и cross-Silo corroboration.
- [`docs/evidence/S02E08-quinn-historical-reset.md`](docs/evidence/S02E08-quinn-historical-reset.md) — historical reset на Quinn, recurring rebellions и reversal на official history.
- [`docs/evidence/S02E08-memory-suppression-water.md`](docs/evidence/S02E08-memory-suppression-water.md) — chronic waterborne memory suppression и cross-episode corroboration.
- [`docs/evidence/S02E08-meadows-quinn-pact.md`](docs/evidence/S02E08-meadows-quinn-pact.md) — разследването на Meadows за Quinn family и старо копие на `Pact Between the Founders`.
- [`docs/evidence/S02E08-quinn-decoded-message.md`](docs/evidence/S02E08-quinn-decoded-message.md) — decoded Quinn payload и формулировката `game is rigged`.
- [`docs/evidence/S02E08-sims-ahundsen-message.md`](docs/evidence/S02E08-sims-ahundsen-message.md) — съобщението на R. Ahundsen до Judge Sims и orchard context.
- [`docs/evidence/S02E08-silo17-multiple-survivors.md`](docs/evidence/S02E08-silo17-multiple-survivors.md)
- [`docs/evidence/S02E09-quinn-safeguard-tunnel.md`](docs/evidence/S02E09-quinn-safeguard-tunnel.md) — Quinn: 50/51 Silos, safeguard и bottom-tunnel verification path.
- [`docs/evidence/S02E09-hidden-lower-contact.md`](docs/evidence/S02E09-hidden-lower-contact.md) — Active lower contact и previous visitors Quinn/Meadows/George.
- [`docs/evidence/S02E09-silo17-vault-knowledge.md`](docs/evidence/S02E09-silo17-vault-knowledge.md) — Knowledge-preservation среда във vault-а на Silo 17.
- [`docs/evidence/S02E09-silo17-survivor-group.md`](docs/evidence/S02E09-silo17-survivor-group.md) — Organized survivor group и “the killer” accusation.
- [`docs/evidence/S02E09-coercive-message.md`](docs/evidence/S02E09-coercive-message.md) — Wife/camera coercive digital message.
- [`docs/evidence/S02E10-safeguard-poison-system.md`](docs/evidence/S02E10-safeguard-poison-system.md) — safeguard poison pipe, Level 14 и Silo 17 block.
- [`docs/evidence/S02E10-silo18-rebellion-return-airlock.md`](docs/evidence/S02E10-silo18-rebellion-return-airlock.md) — Level 123, stair sabotage, Juliette return и corrected airlock chronology.
- [`docs/evidence/S02E10-presilo-washington-georgia-iran-pez.md`](docs/evidence/S02E10-presilo-washington-georgia-iran-pez.md) — direct pre-Silo Washington, disputed radiological narrative, Georgia и PEZ provenance.
- [`docs/open-questions.md`](docs/open-questions.md) — активните въпроси за falsification / future testing.
- [`assets/S01E01/screenshots/`](assets/S01E01/screenshots/) — visual evidence от S01E01.
- [`assets/S01E02/screenshots/`](assets/S01E02/screenshots/) — selected visual evidence от S01E02.
- [`assets/S01E03/screenshots/`](assets/S01E03/screenshots/) — selected visual evidence от S01E03.
- [`assets/S01E04/screenshots/`](assets/S01E04/screenshots/) — selected visual evidence от S01E04.
- [`assets/S01E05/screenshots/`](assets/S01E05/screenshots/) — selected visual evidence от S01E05.
- [`assets/S01E06/screenshots/`](assets/S01E06/screenshots/) — selected visual evidence от S01E06.
- [`assets/S01E07/screenshots/`](assets/S01E07/screenshots/) — validated selected visual evidence от S01E07.
- [`assets/S01E07/MANIFEST.md`](assets/S01E07/MANIFEST.md) — manifest за S01E07 visual processing/selection.
- [`assets/S01E08/screenshots/`](assets/S01E08/screenshots/) — validated selected visual evidence от S01E08.
- [`assets/S01E08/MANIFEST.md`](assets/S01E08/MANIFEST.md) — manifest за S01E08 visual processing/selection.
- [`assets/S01E09/screenshots/`](assets/S01E09/screenshots/) — validated selected visual evidence от S01E09.
- [`assets/S01E09/MANIFEST.md`](assets/S01E09/MANIFEST.md) — manifest за S01E09 visual processing/selection.
- [`assets/S01E10/screenshots/`](assets/S01E10/screenshots/) — validated selected visual evidence от S01E10.
- [`assets/S01E10/MANIFEST.md`](assets/S01E10/MANIFEST.md) — manifest за S01E10 visual processing/selection.
- [`assets/S02E01/screenshots/`](assets/S02E01/screenshots/) — validated selected visual evidence от S02E01.
- [`assets/S02E01/MANIFEST.md`](assets/S02E01/MANIFEST.md) — manifest за S02E01 visual processing/selection.
- [`assets/S02E02/screenshots/`](assets/S02E02/screenshots/) — validated selected visual evidence от S02E02.
- [`assets/S02E02/MANIFEST.md`](assets/S02E02/MANIFEST.md) — manifest за S02E02 visual processing/selection.
- [`assets/S02E03/screenshots/`](assets/S02E03/screenshots/) — validated selected visual evidence от S02E03.
- [`assets/S02E03/MANIFEST.md`](assets/S02E03/MANIFEST.md) — manifest за S02E03 visual processing/selection.
- [`assets/S02E04/screenshots/`](assets/S02E04/screenshots/) — validated selected visual evidence от S02E04.
- [`assets/S02E04/MANIFEST.md`](assets/S02E04/MANIFEST.md) — manifest за S02E04 visual processing/selection.
- [`assets/S02E05/screenshots/`](assets/S02E05/screenshots/) — validated selected visual evidence от S02E05.
- [`assets/S02E05/MANIFEST.md`](assets/S02E05/MANIFEST.md) — manifest за S02E05 visual processing/selection.
- [`assets/S02E06/screenshots/`](assets/S02E06/screenshots/) — validated selected visual evidence от S02E06.
- [`assets/S02E06/MANIFEST.md`](assets/S02E06/MANIFEST.md) — manifest за S02E06 visual processing/selection.
- [`assets/S02E07/screenshots/`](assets/S02E07/screenshots/) — validated selected visual evidence от S02E07.
- [`assets/S02E07/MANIFEST.md`](assets/S02E07/MANIFEST.md) — manifest за S02E07 visual processing/selection.
- [`assets/S02E08/screenshots/`](assets/S02E08/screenshots/) — validated selected visual evidence от S02E08.
- [`assets/S02E08/MANIFEST.md`](assets/S02E08/MANIFEST.md) — manifest за S02E08 visual processing/selection.
- [`assets/S02E09/screenshots/`](assets/S02E09/screenshots/) — validated selected visual evidence от S02E09.
- [`assets/S02E09/MANIFEST.md`](assets/S02E09/MANIFEST.md) — manifest за S02E09 visual processing/selection.
- [`assets/S02E10/screenshots/`](assets/S02E10/screenshots/) — validated selected visual evidence от S02E10.
- [`assets/S02E10/MANIFEST.md`](assets/S02E10/MANIFEST.md) — manifest за Season 2 finale visual processing/selection.

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

**Official record ≠ независимо проверена истина.**

S01E05 дава direct-confirmed example: Sims kills Trumbull → official narrative says suicide → Judge closes case.

Това не означава, че всички official records са false. Означава, че official records се класифицират като institutional claims, когато няма independent corroboration.

### Допълнително правило след S01E06

**Public knowledge loss ≠ total institutional knowledge loss.** Restricted relic DB показва, че selected pre-Silo records са preserved в privileged systems. Hidden surveillance също вече е direct-confirmed infrastructure, а не само dossier inference.

### Допълнително правило след S01E07

**Direct confession / direct observation > историческо обяснение.**

S01E07 съдържа както direct-confirmed механизми, така и historical testimony. Например:
- retained-implant deception е independently corroborated чрез Allison physical evidence + Juliette’s father confession;
- water-based memory suppression и anti-Flamekeeper lineage targeting остават historical claims до independent corroboration;
- Flamekeepers не се приравняват автоматично с Rebels, докато episode evidence не establish-не връзката.

### Допълнително правило след S01E08

**Character belief може да бъде superseded от новонаблюдаван механизъм; institutional testimony само по себе си може да бъде coercive mechanism.**

- По-ранното убеждение на Juliette, че баща ѝ е издал микроскопа, вече не е необходимо, след като mirror surveillance е известно и тя самата свързва двете.
- Твърдението Mayor/Sims „she wants to go out“ се следи отделно от това, което Juliette реално е казала; последвалият арест не прави твърдението ретроактивно вярно.

### Допълнително правило след S01E09

**Evidence, което става известно на персонаж, се следи отделно от evidence, вече известно на зрителя/проекта.**

Jane Carmody cleaning footage вече беше direct visual evidence в S01E01. S01E09 е важно, защото Juliette сама получава достъп до същия evidence; това не прави lush image изведнъж вярно и не решава дали е real vs manipulated.

### Допълнително правило след S01E10

**Character conclusions остават отделни от direct system reveals.** Juliette първоначално заключава, че public display е лъжата, защото helmet-ът ѝ показва lush imagery; S01E10 след това директно разкрива, че самото helmet imagery е false. Затова ledger-ът пази нейното твърдение като character inference, а по-късното reveal — като evidence от по-висок клас.

### Допълнително правило след S02E01

**Cross-Silo repetition укрепва hypotheses за standardization, а не автоматични изводи за central control.** Когато същата architecture се появява във втори Silo — mirror cameras, IT, airlock, agriculture — можем по-силно да infer-нем общ design/doctrine, но не заключаваме автоматично, че една live central authority контролира всеки Silo.

**Superseded inferences остават в history.** E188 запазва първоначалната погрешна Engineering/generator-target interpretation и я маркира като superseded, след като по-късен scene evidence идентифицира IT като действителната attacked/defended location.

### Допълнително правило след S02E02

**Privileged doctrine, insider interpretation и direct mechanism остават отделни evidence classes.** Заглавието в `THE ORDER` е direct institutional evidence; обясненията на Bernard/Meadows за tape са insider testimony; exact engineering mechanism остава unresolved, докато не бъде директно установен.

**Repeated cross-Silo secured architecture подкрепя standardization, а не identical contents.** Подобните IT vault-like compartments в два Silos strengthen-ват H38, без да приемаме, че съдържат едни и същи systems, хора или doctrine.

### Допълнително правило след S02E03

**Historical corroboration укрепва механизъм, без да превръща testimony в objective telemetry.** Silo 17 силно съвпада с `THE ORDER`, но действията на Ron, dust/poison timing и заповедите на Russell остават survivor testimony, освен ако не бъдат independently observed.

**Chronology contradictions се запазват, а не се нормализират насила.** `SILO YEAR 96/97`, `116 A.R.` и приблизителното твърдение на Bernard за Jane Carmody „~200 years“ се пазят като отделни anchors, докато consistent mapping не бъде директно подкрепен.

### Допълнително правило след S02E04

**Crisis narrative може сам по себе си да е engineered mechanism.** Когато doctrine предписва виновник и leadership инсценира събития, които да подкрепят тази narrative, публичното обвинение е evidence за governance behavior, а не evidence, че обвинената група е причинила кризата.

**Internal elite conflict се следи отделно от formal hierarchy.** Classified access на Bernard и political/operational leverage на Sims могат да съществуват едновременно; нито един не се приема като total control над другия без domain-specific evidence.

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


### Допълнително правило след S02E05

**Formal office и hidden succession са отделни evidence layers.** Това, че Bernard назначава Sims за Judge, но му отказва ролята `shadow`, показва, че public institutional rank не означава автоматично access до най-дълбокия IT succession/read-in path.

**Infrastructure-line drawings не се интерпретират сами.** Линия, стигаща до IT или Judicial, се записва като connection/path на schematic; power, data, communications, control и utility interpretation остават competing, докато diagram или dialogue не идентифицира service-а.



### Допълнително правило след S02E06

**Съществуване на technology ≠ universal access до нея.** Direct messaging на institutional terminals доказва, че Silo има digital communication capability, но не доказва, че обикновените residents имат равен endpoint/account access.

**Communication channels се моделират отделно според access и control.** Courier, digital messaging и radio могат да съществуват паралелно, защото обслужват различни populations/functions. Способността на IT да cut-ва radio е evidence за control върху този channel, а не автоматично доказателство, че IT чете всяко digital message или контролира всяка physical communication.

**Near-real-time field reporting ≠ direct source-terminal proof.** Control-room report установява digital HUMINT/field-report pipeline, но originating device, intermediary и protocol остават unresolved.



### Допълнително правило след S02E07

**Protected knowledge preservation ≠ public historical continuity.** Library-то `Legacy` показва, че privileged historical/technical knowledge може да бъде умишлено запазено, докато обикновените residents губят или нямат достъп до широк historical context.

**Functional redundancy ≠ identical source architecture.** Това, че IT в Silo 18 остава powered при blackout, доказва continuity/redundant power, но само по себе си не доказва същия external source, описан за Silo 17.

**Circulating message ≠ verified authorship or truth.** Anti-IT leaflet-ът е direct evidence, че counter-narrative съществува. Неговите claims, author, distributor и official Mechanical endorsement се следят отделно.

**Derived chronology запазва approximation.** `352 years since construction - ~140 years since Rebellion ≈ 212 pre-Rebellion years` е strong derived anchor, но approximate testimony inputs не се превръщат мълчаливо в exact calendar dates.



### Допълнително правило след S02E08

**Privileged historical testimony може да отхвърли official account, без автоматично да се превръща в omniscient truth.** Bernard директно идентифицира публичната Quinn story като невярна и дава coherent hidden mechanism, но мотивите на Quinn и causal claim-ът, че самата historical memory е пораждала rebellions, остават tracked като privileged historical testimony.

**Corroborated mechanism ≠ identical substance.** S01E07 water-memory testimony + S02E08 account на Bernard силно установяват historical waterborne memory suppression, докато S02E03 доказва, че съществува current forgetfulness medication. Exact compound identity между eras остава unresolved.

**Historical erasure и historical preservation могат да съществуват едновременно по design.** Public records/books/memory могат да бъдат suppress-нати, докато `Legacy` и други privileged systems пазят selected truth. Моделът е controlled access, а не total destruction.

**Association със стар документ ≠ authorship.** Ръкописното `Salvador Quinn` върху `The Pact Between the Founders` го асоциира директно с това копие, но не установява, че е автор на Pact, че е Founder или че е променял текста му.

**Decoded phrase ≠ decoded system.** `the game is rigged` е direct evidence от съобщението на Quinn, но exact referent на `the game` остава open.


## Текущ модел за външния свят

След S02E08 основната exterior visual ambiguity остава разрешена. S02E08 does not materially alter the exterior-hazard model; it directly changes the Silo 17 habitation model by confirming multiple living inhabitants:

1. **Lush cleaner view is false** — helmet-ът показва manipulated / overlay-like visual layer.
2. **Barren exterior is substantially real** — след отпадането на false layer Juliette вижда devastated terrain.
3. **Съществуват multiple Silo installations**; survivor от Silo 17 заявява exact system count **50**.
4. В далечината се вижда **ruined / city-like skyline**, но identity/location не са установени.
5. Juliette директно достига и влиза във **втори Silo**.
6. Голямо mass-remains field около този Silo потвърждава real lethal exterior hazard при наблюдаваните условия.
7. Текущият best-fit hazard class е **mobile airborne/dust-borne hazard**, чиято local concentration може временно да се разсее и после да се върне; exact toxin/pathogen/particulate mechanism остава unresolved.
8. Suit sealing и breathing-support integrity влияят съществено върху survival.
9. Insider dialogue силно свързва оцеляването на Juliette със замяната на normal cleaning tape с по-добър seal.
10. Bernard/IT получава live exterior video, свързано с Juliette, докато тя е навън.
11. Silo 17 показва, че ако expected death на cleaner не бъде наблюдавана, може да възникне belief „outside is safe“ и mass-exit cascade.
12. Juliette изрично идентифицира repeated lush visual sequence като cleaning-behavior trigger.
13. Bernard демонстрира standalone immersive headset с preserved pre-Silo natural environment и обяснява, че работи подобно на cleaner-helmet imagery.
14. S02E08 директно потвърждава multiple living inhabitants в Silo 17 отвъд познатия досега IT-vault survivor.

Все още са unresolved exact helmet-rendering technology, exact outside lethal agent, exact suit leak pathway, exact source/format of the live cleaner feed, independent confirmation of the 50-Silo count, full Silo-numbering scheme, any current central authority and identity-то на distant skyline.

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
episode/S02E03-analysis
episode/S02E04-analysis
episode/S02E05-analysis
episode/S02E06-analysis
episode/S02E07-analysis
episode/S02E08-analysis
hypothesis/<name>
model/<name>
methodology/<change>
```

Git history е част от разследването: трябва да можем да видим кога е възникнала една theory, кой evidence я е укрепил, кой я е отслабил и кога е била refactor-ната или отхвърлена.

---

**Следваща knowledge boundary:** `S03E01`
