# Проект SILO — обратен анализ на проектирана система за оцеляване

Дневник за систематичен анализ, воден от evidence и стриктно спазващ spoiler границите, на телевизионния сериал **Silo**.

Целта е да третираме света на сериала като **черна кутия**: наблюдаваме поведението на системата, извличаме възможни правила, изграждаме конкуриращи се hypotheses и ги променяме или отхвърляме, когато нови епизоди дадат по-добър evidence.

> **След S03E04 архитектурата за контрол вече е видимо вътрешно оспорвана: неизвестен участник нагоре по веригата използва медицинска сестра за скрита подмяна на хапчетата на Juliette за потискане на паметта; медицинската сестра и съюзник от Mechanical подпомагат маршрута ѝ за бягство, а скрит достъп до дълбоката зона я отвежда до Bernard — жив. Това опровергава предишния разказ за смъртта/изгарянето на Bernard. Междувременно Pre-Silo линията показва персонализирано привличане и обратно обаждане от Пентагона с извънредно откритие.**

## Език на проекта

Основният език на repo-то е **български**.

Всички обяснителни текстове, анализи, заключения, въпроси и описания се пишат на български. Утвърдени технически термини могат да останат на английски, когато това прави модела по-точен или по-четим — например `evidence`, `confidence`, `hypothesis`, `knowledge boundary`, `direct observation`, `institutional claim`, `visual pipeline`, `feed`, `overlay`, `falsification`, `branch` и `PR`.

Имената на файлове, branch-ове, code identifiers и оригинални UI/file labels от сериала не се превеждат задължително.

### Задължително езиково правило

**Обяснителният prose в repo-то се пише на български.**

Английски могат да останат:
- утвърдени project/technical terms като `evidence`, `confidence`, `hypothesis`, `knowledge boundary`, `direct observation`, `institutional claim`, `feed`, `overlay`, `branch`, `PR`;
- точни цитати от сериала; оригиналът се запазва дословно, а при важни цитати веднага след него може да се добави български превод в скоби, без преводът да заменя оригиналния evidence;
- обяснителният текст около цитатите остава на български;
- оригинални UI/document labels като `THE ORDER`, `DIRECT MESSAGING`, `SERVER ROOM`, `Legacy`;
- filenames, paths, branch names и code identifiers;
- собствени имена.

**Цели английски обяснителни изречения не се използват**, освен когато са точен цитат или оригинален текст от UI/document evidence.

## Knowledge boundary

**Текуща граница на знанието:** **S03E04**

**Статус на гледане:** **Season 3 — S03E04 завършен**

Не се използва никаква информация след S03E04, книги, wiki, interviews, бъдещи synopses, leaks или retrospective explanations.

## Текущо състояние

След S03E04 най-силният работен модел е:

> **Системата на Silo се моделира като многослойна архитектура за оцеляване и контрол с мощен надзорен слой, но не и с монолитен човешки изпълнителен механизъм. Потискането на паметта може да бъде тайно саботирано отвътре; Juliette има верига за подкрепа от няколко души; до дълбоката зона има скрит функционален достъп; привидната смърт на Bernard е опровергана; точните координатори, йерархията на контрола и дългосрочната цел остават неустановени.**

Ключови установени линии:

- cleaner lush view остава repeatable при Allison, Jane Carmody и Holston;
- публичният екран обичайно показва безплодна външна среда;
- S01E03 изключването на захранването показва зелено състояние на самия public display;
- S01E04 показва normal night state;
- S01E05 показва систематично, зависещо от времето движение на звездоподобни светлини върху нощния екран;
- наблюдателят в cafeteria не познава понятието „звезди“ и сам реконструира модели на движение;
- Silo има **144 levels** и Bernard заявява **10 112 current residents**;
- директно наблюдаваните ориентири по нива вече включват `1, 8, 9, 12, 14, 17, 23, 26, 27, 29, 30, 50, 55, 67, 70, 76, 87, 119, 120, 123, 124, 144`;
- Pact умишлено забранява механизиран транспорт през Silo;
- Pact забранява увеличителни устройства над определен праг;
- досието на Juliette съдържа информация от разговора ѝ с Holston → силно доказателство за скрито наблюдение/докладване;
- Douglas Trumbull е хванат да манипулира/подхвърля evidence и се опитва да убие Juliette;
- Sims лично убива Trumbull, после представя смъртта му като suicide;
- Judge формално приключва случая след този невярен разказ;
- следователно официалният институционален запис не може автоматично да се третира като независимо установена истина;
- Juliette търси формално основание за повторно отваряне на случая George и взема PEZ реликвата от зоната под Silo;
- `The Syndrome` е изричен термин в света на сериала; S01E06 установява новия Deputy като конкретно засегнат персонаж, но естеството/причината остават неизвестни;
- **няма установена връзка Syndrome ↔ увеличение** — това остава само VL спекулация/отворен въпрос;
- централизиран control center за наблюдение с множество feeds наблюдава множество вътрешни места, включително Juliette в дома ѝ;
- ограничената Judicial база данни за реликви пази архивни `PRE-SILO` записи, а Sims/Judicial има привилегирован достъп;
- Pre-Silo пътеводителят за Georgia установява конкретна география в САЩ/Georgia, но не локализира Silo;
- Sims оперативно командва наблюдението; Judge Meadows и medical center са наблюдавани;
- скритите камери са потвърдени зад/в огледалата, а достъпът до контролния център минава през скрит маршрут през служебно помещение на Janitorial;
- Flamekeepers са описани като група, съхраняваща историята/relics; точната им връзка с Rebellion остава неустановена;
- историческо свидетелство въвежда потискане на паметта чрез водата преди/около ерата на Rebellion;
- бащата на Juliette лично признава измамата с премахването на импланта, потвърждавайки скрит механизъм за репродуктивен контрол;
- Juliette и George са свързани чрез своите Flamekeeper майки и междупоколенческа мрежа за съхраняване;
- наблюдаваните level anchors вече включват и Level 26 и **Level 30**;
- майката на Juliette използва самоделен микроскоп/увеличително устройство за независимо медицинско изследване; записите с ограничен достъп показват институционално внимание към тази дейност;
- Juliette осъзнава, че mirror surveillance може да обясни откриването на микроскопа на майка ѝ, без да е нужен моделът father-as-informant;
- приоритетно съобщение Medical → Martha Walker директно потвърждава структурирани междуведомствени цифрови съобщения;
- Mayor + Sims координират капан и твърдят, че Juliette е казала, че иска да излезе навън; тя е арестувана на тази основа;
- Bernard/IT твърди, че Judge Meadows се страхува от него; обективната йерархия остава неустановена;
- S01E08 завършва с Juliette, която преминава през парапета в контекст на бягство/избягване;
- S01E09 разрешава непосредствения резултат: тя оцелява след първоначалното падане върху междинен мост на **Level 23**;
- показан е малък осветен object/device с маркировка **`18`** в контекст с Bernard/acting mayor; функцията е неизвестна и не се приема автоматична връзка с HDD 18;
- Juliette отваря познатия файл **`JANE CARMODY CLEANING`** от evidence веригата на hard drive-а, което прави алтернативното зелено cleaning изображение част от собственото ѝ знание;
- S01E10 разкрива, че зелената гледка за cleaner-а/шлема е **неверен визуален слой**; първоначалното убеждение на Juliette, че public display лъже, е заменено от директното разкритие;
- безплодната външна среда остава видима след отпадането на невярния слой и следователно е в значителна степен реална;
- Bernard разпознава, че Juliette е разбрала измамата с шлема, и демонстрира привилегирован достъп/контрол върху класифицираната cleaning информация и наблюдението;
- Bernard може да спре чувствително излъчване и да нареди на персонала в control room, включително Sims, да не гледа/запазва видяното;
- костюмът на Juliette използва различна лента/материал и тя оцелява отвъд момента, в който Bernard/Sims очакват cleaner да умре, което силно посочва уплътняването на костюма;
- осветеният object `18` е директно показан като **physical key**; какво отключва и дали е свързан с HDD 18 остават неизвестни;
- широките външни кадри разкриват **множество Silo инсталации** и далечен разрушен/подобен на град силует;
- Level 144/bottom съдържа голяма ventilation / air-handling machinery;
- официалната табела `THE SYNDROME` дава частично четима symptom progression;
- Janitorial съдържа структурирана `ROTA` таблица по ден/ниво/час.
- S02E01 директно поставя Juliette при и вътре във **втори Silo**, превръщайки модела за множество Silos от външно наблюдение в директно изследване;
- началната историческа последователност във втория Silo показва графити срещу Основателите/измамата, настъпление срещу IT, водено от Sheriff, пробив на airlock-а и масово излизане навън;
- в сцените от настоящето Juliette намира голямо поле от човешки останки около люка на втория Silo, което силно потвърждава реална смъртоносна външна опасност;
- Juliette изпитва acute breathing distress, докато е sealed в suit-а си вътре във втория Silo, а след отваряне/разбиване на helmet-а отново може да диша; exact breathing technology остава неизвестна;
- текущият най-подходящ клас за външната опасност е **въздушно / атмосферно излагане**; токсин/химикал/аерозол и патоген остават конкуриращи се възможности;
- вторият Silo съдържа същата концепция за скрити камери в огледалата, което силно подкрепя стандартизиран cross-Silo дизайн за наблюдение/контрол;
- IT във втория Silo е защитена стратегическа зона с прекъснат достъп, локално осветление и помещение, подобно на vault;
- вторият Silo е масивно наводнен до няколко нива под IT, но не е напълно electrically dead;
- поне един жив човек остава вътре в secured IT compartment;
- показана е младата Juliette, която като дете посещава excavation machine в своя Silo;
- точният общ брой Silos и всяка връзка `key 18 ↔ HDD 18 ↔ Silo 18` остават неустановени.
- S02E02 показва как Bernard/IT получава **live Juliette-associated exterior video feed**; сигналът се губи, когато тя влиза във втория Silo;
- Bernard използва отделна физическа doctrine, озаглавена **`THE ORDER`**;
- `THE ORDER` изрично гласи **`IN THE EVENT OF A FAILED CLEANING, PREPARE FOR WAR`**;
- Judge Meadows знае за `THE ORDER`, следователно тази hidden doctrine не е лична тайна на Bernard;
- Bernard изрично се страхува, че катастрофалната съдба на втория Silo може да се повтори и в неговия;
- Bernard и Meadows приписват оцеляването на Juliette на замяната на normal cleaning tape;
- Meadows казва, че някой рано или късно ще разбере механизма с лентата, а по-късно изисква **добра лента**, преди да се съгласи да излезе навън;
- стандартната cleaning лента следователно е силно подкрепена като умишлено/системно по-лоша, макар проникване на замърсител спрямо загуба на дихателен газ спрямо комбинация от двете да остава неустановено;
- Silo на Bernard съдържа защитен IT слой с помещение, подобно на vault, аналогичен на защитеното IT помещение във втория Silo;
- появява се отличителен ограден символ/емблема в контекста на бунта; точното му значение остава неизвестно.
- свидетелството на оцелелия в S02E03 идентифицира другата инсталация като **Silo 17** и заявява **50 Silos**; материалът на Quinn в S02E09 независимо казва, че Основателите са построили **50**, но Bernard уточнява, че реалният брой е **51**; причината за несъответствието остава неустановена, а оригиналният Silo на Juliette е силно идентифициран/изводим като **Silo 18**;
- отказът на Ron да почисти, съобщението `LIES` и изчезването му от полезрението са последвани от вътрешно съобщение `LIES` и бунт в Silo 17;
- оцелелият от Silo 17 казва, че хората по-късно излизат, защото не виждат Ron да умира и заключават, че външната среда е безопасна; това силно потвърждава видимата смърт на cleaner-а като възпиращ фактор за населението;
- жителите на Silo 17 са описани като оцелели навън, докато прахът/отровата временно се разсейва, след което умират при завръщането на опасността; реалната смъртоносност на външната среда и обичайният времеви прозорец за смърт на cleaner-а следователно са различни механизми;
- IT compartment-ът в Silo 17 е изрично наречен **vault**; Russell поставя survivor-а вътре и му нарежда да не допуска никого;
- physical key `18` на Bernard дава достъп до **SERVER ROOM**, а vault-ът е вътре в него;
- Bernard казва, че Jane Carmody cleaning recording е на около **200 години**, и е знаел, че Silo 17 е "dead", много преди текущата криза;
- Sims изрично предлага лекарство, за да може човек да **забрави**, което независимо потвърждава фармакологична способност за потискане на паметта;
- `CODE SILO ORANGE` директно инструктира medical staff да не премахва birth control, като гарантира, че patient вярва, че е премахнат;
- същият medical record използва `DOB 09/13/116 A.R.`, което налага chronology на H15 да бъде weakened/refactored, а не мълчаливо запазена;
- Juliette изрично идентифицира зелената cleaning гледка като поведенчески trigger за почистването и разпознава измамата по повторения визуален модел от Jane Carmody, включително същото движение на летящите същества;
- Judge Meadows излага теория, че The Syndrome може да е реакция към живота в Silo, а не primary physiological disease.
- S02E04 разкрива, че `THE ORDER` инструктира leadership да обвинява **Mechanical** при rebellion/crisis;
- historical markings в Mechanical се интерпретират като знак, че Mechanical многократно е бил обвиняван независимо откъде реално започва unrest;
- текущото best explanation за избора на Mechanical е контролът му върху generator/critical infrastructure, но това остава hypothesis;
- мините осигуряват metal, използван в Silo, а опасната/нежелана mining работа се изпълнява частично чрез **penal labor system**;
- оцелелият от Silo 17 е бил дете по време на бунта и е бил поставен/заключен в IT vault още от детството, което засилва интерпретацията за приемственост и убежище за оцеляване;
- Level **119** е директно наблюдаван като нов spatial anchor;
- Bernard отравя Judge Meadows;
- Meadows пита за hard drive, свързан със **Salvador Quinn**, описан като Head of IT по време на Rebellion преди приблизително 140 години;
- Quinn оставя писмо, което е поне частично encoded;
- Meadows напуска shadow path на Bernard преди около 25 години след четиридневно изчезване;
- Bernard демонстрира immersive headset, показващ Monteverde cloud forest, 2018, и обяснява, че работи подобно на cleaner-helmet visual technology;
- Bernard дава този headset на Meadows преди смъртта ѝ;
- Bernard инсценира пристигането на представители на Mechanical на мястото на смъртта на Meadows, за да може Mechanical да бъде обвинен и public anger да бъде пренасочен към тях;
- Bernard твърди, че impeachment protests са го принудили да действа, и казва, че Sims стои зад натиска;
- Sims активно насочва публичните нагласи срещу Mechanical, демонстрирайки значимо независимо политическо/оперативно влияние;
- S02E04 завършва с large-scale population movement по време на escalating unrest.
- S02E05 показва как Bernard отстранява Sims като Head of Security, изрично му отказва ролята `shadow` и го назначава за Judge;
- това разделя публичната длъжност в Judicial от привилегирования IT път за наследяване/read-in на Bernard, без да доказва, че всеки Judge е просто марионетка;
- оцелелият от Silo 17 казва, че IT има собствено независимо електрозахранване от външен източник спрямо нормалния път през генератора;
- pump на Level 144 е унищожена по време на rebellion в Silo 17, за да бъде наводнен Mechanical; покачващата се вода в крайна сметка изключва main generator и продължава да се покачва;
- оцелелият иска Juliette да ремонтира помпа и да я захрани от IT, което предполага, че резервното захранване може потенциално да поддържа избрани товари за възстановяване извън IT;
- Level 26 отново е директно показан като repeated spatial anchor;
- директно е показано голямо multilevel landscaped common/circulation area;
- новооткрита схема на Silo показва маркирани линии, свързани в контекста на сцената едновременно с IT и Judicial; типът и източникът на линиите остават неустановени;
- в архива е намерено scanned handwritten писмо на Salvador Quinn;
- encoded/ciphered material е конкретно в края на писмото на Quinn, което refine-ва по-ранното описание 'partly encoded'.
- S02E06 директно показва Sheriff Department `DIRECT MESSAGING` interface с departmental и named senders;
- директно е показан двупосочен цифров разговор между хора;
- това отслабва всеки модел, според който куриерите съществуват просто защото електронните съобщения не съществуват;
- control room получава маршрутизиран писмен полеви доклад за движението и оборудването на въоръжена група;
- точното изходно устройство/входен път, използван от информаторите на терен, остава неустановено;
- Bernard/IT може да прекъсва всички radio communications в Silo, установявайки centralized communications-control capability;
- най-силният комуникационен модел вече съдържа поне три паралелни нива: физически куриери, институционално digital messaging и централизирано контролируемо радио;
- Level 55 и Level 120 стават нови директни пространствени ориентири.
- S02E07 разкрива жилищни/обитаеми помещения вътре в защитения IT vault;
- protected vault component, наречен `Legacy`, е идентифициран като library / knowledge archive;
- `Legacy` дава конкретен механизъм привилегированата институционална памет да оцелява през поколения/наследяване;
- Bernard заявява, че Silo е построен преди **352 години**;
- комбинирано с ~140-years-ago Rebellion anchor, construction е приблизително **212 години преди Rebellion**;
- handwritten leaflet гласи `I.T. Lies to us`, `Mechanical wants THE TRUTH`, пита какво се е случило с Juliette, как наистина е умряла Meadows и какво крие IT;
- leaflet-ът установява circulating anti-IT counter-narrative, но не и неговия author/distributor;
- по време на general Silo 18 blackout IT остава видимо powered и жителите изрично забелязват изключението;
- захранването за приемственост следователно е независимо демонстрирано поне в Silos 17 и 18, докато точното съответствие на източника остава неустановено.
- S02E08 разкрива привилегирована алтернативна история според Bernard: Quinn не се е провалил по време на Rebellion, а умишлено е прекъснал публичната историческа приемственост;
- Bernard казва, че бунтовете преди Quinn са се повтаряли приблизително на всеки 20 години и всеки е застрашавал целия Silo;
- Quinn премахва публичния достъп до server записите, конфискува книги и позволява/причинява историческата загуба да бъде приписана на бунтовниците;
- Bernard казва, че Quinn поставя химикал/лекарство, потискащо паметта, във водата; хроничното излагане в течение на седмици, месеци и години кара спомените да избледняват;
- това независимо потвърждава по-ранното Flamekeeper свидетелство за паметта и водата и силно засилва модела за фармакологично потискане на паметта;
- Bernard приписва приблизително 140 години мир на намесата на Quinn, докато тази причинна диагноза остава привилегирована интерпретация, а не независимо доказателство;
- по-ранното разследване на Quinn от Meadows вече е свързано с роднините на Quinn и оцелели книги/материали;
- старо копие със заглавие `The Pact Between the Founders` носи ръкописното име `Salvador Quinn`; връзката е пряка, но авторството/статусът на Основател не са установени;
- декодираното съобщение на Quinn гласи: `If you've gotten this far, you already know the game is rigged.` („Ако си стигнал дотук, вече знаеш, че играта е нагласена.“);
- Judge Sims получава лично съобщение от R. Ahundsen, в което се споменават погребение и `little apple tree`; голяма овощна градина дава правдоподобен буквален референт, но евентуален кодиран замисъл остава неустановен;
- Silo 17 директно съдържа множество живи обитатели, не само познатия досега оцелял от IT vault-а.
- S02E09 показва организирана група от допълнителни оцелели в Silo 17; групата нарича оцелелия от IT vault-а `the killer` („убиецът“) и го използва като средство за натиск за храна;
- vault-ът на Silo 17 директно съдържа голяма среда от книги, архиви и научно знание, функционално аналогична на `Legacy` в Silo 18, без официалното обозначение `Legacy` да е потвърдено;
- decoded Quinn material казва: `The founders didn't build a single silo. They built fifty.` и `And they created the safeguard.`;
- Bernard отделно заявява, че реалният брой е **51**, а Heads of IT и `shadows` знаят за другите Silos;
- Quinn оставя последователни указания за физическа проверка: `go to the very bottom` („слез до самото дъно“) → `find the tunnel` („намери тунела“) → `you will get confirmation there` („там ще получиш потвърждение“);
- наблюдаваната долна зона на Silo 18 е плитка/проходима, а реален тунел/отвор действително е намерен;
- в тунела/долната зона активен неизвестен събеседник/система води двупосочен разговор с Lukas, отчитащ контекста;
- lower contact казва, че преди Lukas само **Salvador Quinn, Mary Meadows и George Wilkins** са достигали до тази точка;
- Bernard не е сред предишните посетители; това доказва, че не е посещавал мястото, а не автоматично невежество;
- Lukas е предупреден, че разкриването на видяното/наученото там ще доведе до задействане на `the safeguard`; точният механизъм, контролиращ субект и ефект остават неустановени в S02E09;
- shadow-ът на Bernard спекулира за hidden pumps под known bottom, неизвестни на Mechanical; това остава speculation;
- цифрово принудително съобщение изисква включена камера/забрана за напускане и използва съпругата като средство за натиск; самоличността на подателя/получателя не се извежда само от screenshot-а.

- S02E10 директно потвърждава Level 123 и показва саботаж на стълбището, който оперативно разделя силите на Bernard;
- `the safeguard` вече е physical poison-delivery pipe, capable of whole-Silo kill;
- оцелелият от Silo 17 казва, че родителите му са успели да блокират safeguard-а;
- safeguard supply идва отвън и влиза при Level 14;
- това преработва модела: външната опасност и safeguard-ът са отделни смъртоносни механизми;
- Juliette се връща в Silo 18 и показва `not safe / do not come out`;
- Bernard лично я посреща при airlock-а;
- Juliette казва, че **може би знае как да спре safeguard-а**;
- коригираната sequence е: stopping claim → Juliette + Bernard enter → burner/flame cycle;
- финалът показва direct pre-Silo Washington scene;
- radiation screening е routine enough да се използва пред bar;
- central character е Congressman from Georgia's 15th congressional district;
- alleged radiological attack е attributed to Iran, но dialogue-ът поставя под въпрос дали attack изобщо е имало;
- possible retaliatory strike срещу Iran е част от политическия разговор, не established executed action;
- конгресменът подарява PEZ дозатор с жълто пате; това е силен кандидат за връзка по произход към по-ранната Silo-era жълта пластмасова реликва със синя дръжка, без да е доказана точна приемственост на един и същ предмет.

- S03E04 медицинската сестра директно потвърждава, че хапчетата на Juliette за потискане на паметта са били тайно подменяни още преди Juliette сама да започне да ги изплюва;
- unknown upstream actor е казал на nurse-а да започне substitution-а;
- помпената станция на Level 76 е нов директен пространствен/оперативен ориентир по маршрута за бягство на Juliette;
- скрита врата → непокътнат тунел → фиксирана система с въже за спускане осигурява функционален скрит достъп към пропастта/дълбоката изкопна зона;
- Juliette намира Bernard **жив** в дълбоката зона → предишният разказ за смъртта/изгарянето му е заменен и опроверган като текуща истина;
- Keen характеризира Iran recording-а като aircraft no longer controlled by pilots; „hacked“ е analogy, не established cyber mechanism;
- повтарящият се Pre-Silo мъж видимо използва персонализирани стимули: предложение от The Times за журналистката и продължаване на лечението на сестрата на Keen;
- контактът в Пентагона се връща след ~седмица с извънредно откритие; точното съдържание остава неустановено.

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
- [`docs/episodes/S03E01.md`](docs/episodes/S03E01.md) — episode record за S03E01.
- [`docs/episodes/S03E02.md`](docs/episodes/S03E02.md) — episode record за S03E02.
- [`docs/episodes/S03E03.md`](docs/episodes/S03E03.md) — episode record за S03E03.
- [`docs/episodes/S03E04.md`](docs/episodes/S03E04.md) — episode record за S03E04.
- [`docs/evidence/S03E04-memory-escape-network.md`](docs/evidence/S03E04-memory-escape-network.md) — подмяна на хапчетата, намеса на медицинската сестра и скрита верига за бягство/подкрепа.
- [`docs/evidence/S03E04-presilo-cooptation-pentagon.md`](docs/evidence/S03E04-presilo-cooptation-pentagon.md) — избягването на Keen/журналистката, предложенията за привличане и обратното обаждане от Пентагона.
- [`docs/evidence/S03E04-deep-route-bernard.md`](docs/evidence/S03E04-deep-route-bernard.md) — скритият маршрут към пропастта и корекцията, че Bernard е жив.
- [`assets/S03E04/MANIFEST.md`](assets/S03E04/MANIFEST.md) — manifest на визуалното evidence за S03E04.
- [`docs/evidence-ledger.md`](docs/evidence-ledger.md) — evidence регистър с confidence и epistemic class.
- [`docs/evidence/S01E01-exterior-visual-contradiction.md`](docs/evidence/S01E01-exterior-visual-contradiction.md) — focused exterior evidence след S01E01.
- [`docs/evidence/S01E02-holston-visual-split.md`](docs/evidence/S01E02-holston-visual-split.md) — simultaneous cleaner/public visual split при Holston.
- [`docs/evidence/S01E02-sub-silo-construction-layer.md`](docs/evidence/S01E02-sub-silo-construction-layer.md) — hidden construction layer под Silo.
- [`docs/evidence/S01E03-public-display-powerdown-flash.md`](docs/evidence/S01E03-public-display-powerdown-flash.md) — зеленото състояние на публичния екран при изключване на захранването.
- [`docs/evidence/S01E04-sheriff-succession-and-control.md`](docs/evidence/S01E04-sheriff-succession-and-control.md) — Judicial/IT opposition и Sheriff succession conflict.
- [`docs/evidence/S01E05-surveillance-trumbull-coverup.md`](docs/evidence/S01E05-surveillance-trumbull-coverup.md) — наблюдението, натопяването на Trumbull и невярният разказ за самоубийство.
- [`docs/evidence/S01E05-celestial-observation.md`](docs/evidence/S01E05-celestial-observation.md) — star-like temporal behavior и lost astronomical knowledge.
- [`docs/evidence/S01E05-pact-capability-restrictions.md`](docs/evidence/S01E05-pact-capability-restrictions.md) — mechanized-transport и magnification restrictions.
- [`docs/evidence/S01E06-centralized-surveillance.md`](docs/evidence/S01E06-centralized-surveillance.md) — директно потвърдено централизирано вътрешно наблюдение.
- [`docs/evidence/S01E06-relic-database-pre-silo.md`](docs/evidence/S01E06-relic-database-pre-silo.md) — PEZ lookup, Judicial relic DB и preserved pre-Silo knowledge.
- [`docs/evidence/S01E06-georgia-relic.md`](docs/evidence/S01E06-georgia-relic.md) — pre-Silo geographic clue за Georgia, USA.
- [`docs/evidence/S01E07-surveillance-command-and-mirrors.md`](docs/evidence/S01E07-surveillance-command-and-mirrors.md) — командването на Sims, камерите в огледалата и скритата архитектура за наблюдение.
- [`docs/evidence/S01E07-flamekeepers-memory-erasure.md`](docs/evidence/S01E07-flamekeepers-memory-erasure.md) — Flamekeepers, съхраняването на реликви и твърдението за въздействие върху паметта чрез водата.
- [`docs/evidence/S01E07-reproductive-control.md`](docs/evidence/S01E07-reproductive-control.md) — doctor confession и reproductive-control mechanism.
- [`docs/evidence/S01E07-flamekeeper-family-network.md`](docs/evidence/S01E07-flamekeeper-family-network.md) — intergenerational Flamekeeper връзка между Juliette и George.
- [`docs/evidence/S01E08-illicit-microscopy-and-mirror-surveillance.md`](docs/evidence/S01E08-illicit-microscopy-and-mirror-surveillance.md) — микроскопът, записът с ограничен достъп и преразглеждането на модела „бащата е информатор“.
- [`docs/evidence/S01E08-fabricated-cleaning-trigger.md`](docs/evidence/S01E08-fabricated-cleaning-trigger.md) — Mayor/Sims trap, disputed exit claim и arrest.
- [`docs/evidence/S01E08-bernard-judge-power.md`](docs/evidence/S01E08-bernard-judge-power.md) — Bernard’s claim за Judge Meadows и hidden hierarchy candidate.
- [`docs/evidence/S01E09-level23-escape.md`](docs/evidence/S01E09-level23-escape.md) — приземяване върху мост на Level 23 и резултатът от бягството.
- [`docs/evidence/S01E09-number18-device.md`](docs/evidence/S01E09-number18-device.md) — illuminated object/device с маркировка `18`, с неизвестна функция.
- [`docs/evidence/S01E09-jane-carmody-cleaning.md`](docs/evidence/S01E09-jane-carmody-cleaning.md) — Juliette отваря познатото cleaning видео на Jane Carmody.
- [`docs/evidence/S01E10-cleaning-helmet-tape.md`](docs/evidence/S01E10-cleaning-helmet-tape.md) — невярният визуален слой в шлема, различната лента и механизмът за оцеляване на cleaner-а.
- [`docs/evidence/S01E10-bernard-compartmentalization.md`](docs/evidence/S01E10-bernard-compartmentalization.md) — привилегированият достъп/контрол на Bernard и ограничаването на информацията за Sims.
- [`docs/evidence/S01E10-multiple-silos-exterior.md`](docs/evidence/S01E10-multiple-silos-exterior.md) — безплодната реалност, полето от множество Silos и далечният силует.
- [`docs/evidence/S01E10-key18.md`](docs/evidence/S01E10-key18.md) — physical key с маркировка `18`.
- [`docs/evidence/S01E10-syndrome-level144-rota.md`](docs/evidence/S01E10-syndrome-level144-rota.md) — Syndrome sign, Level 144 infrastructure и Janitorial ROTA.
- [`docs/evidence/S02E01-other-silo-rebellion.md`](docs/evidence/S02E01-other-silo-rebellion.md) — rebellion във втория Silo, IT assault и mass exit.
- [`docs/evidence/S02E01-outside-hazard-suit-breathing.md`](docs/evidence/S02E01-outside-hazard-suit-breathing.md) — outside hazard, suit seal и breathing-support model.
- [`docs/evidence/S02E01-cross-silo-surveillance-it.md`](docs/evidence/S02E01-cross-silo-surveillance-it.md) — повторено наблюдение чрез камери в огледалата и стандартизация на IT.
- [`docs/evidence/S02E01-power-flooding-survivor.md`](docs/evidence/S02E01-power-flooding-survivor.md) — residual power, flooding и surviving occupant.
- [`docs/evidence/S02E02-the-order-failed-cleaning.md`](docs/evidence/S02E02-the-order-failed-cleaning.md) — `THE ORDER`, failed-cleaning contingency и war-risk doctrine.
- [`docs/evidence/S02E02-live-cleaner-feed.md`](docs/evidence/S02E02-live-cleaner-feed.md) — live feed от външната среда, свързан с Juliette, и границата на предаването.
- [`docs/evidence/S02E02-cleaning-tape-mechanism.md`](docs/evidence/S02E02-cleaning-tape-mechanism.md) — разграничение между добра/лоша лента и модел на ограничена защита.
- [`docs/evidence/S02E02-it-vault-governance.md`](docs/evidence/S02E02-it-vault-governance.md) — повторената защитена IT архитектура и привилегированият read-in слой.
- [`docs/evidence/S02E03-silo17-failed-cleaning-rebellion.md`](docs/evidence/S02E03-silo17-failed-cleaning-rebellion.md) — failed cleaning в Silo 17, visible-death deterrence и rebellion cascade.
- [`docs/evidence/S02E03-outside-hazard-cleaner-death.md`](docs/evidence/S02E03-outside-hazard-cleaner-death.md) — подвижната външна опасност спрямо обичайния времеви прозорец за смърт на cleaner-а.
- [`docs/evidence/S02E03-memory-suppression.md`](docs/evidence/S02E03-memory-suppression.md) — текуща целенасочена фармакологична способност за предизвикване на забравяне.
- [`docs/evidence/S02E03-key18-server-room-vault.md`](docs/evidence/S02E03-key18-server-room-vault.md) — `key 18 → SERVER ROOM → vault` и protected-vault evidence от Silo 17.
- [`docs/evidence/S02E03-silo-orange-chronology.md`](docs/evidence/S02E03-silo-orange-chronology.md) — formal reproductive-control protocol, `116 A.R.` и chronology correction.
- [`docs/evidence/S02E03-cleaner-perception-pattern.md`](docs/evidence/S02E03-cleaner-perception-pattern.md) — повторен Jane visual pattern, cleaning trigger и изгубен natural-world vocabulary.
- [`docs/evidence/S02E04-mechanical-scapegoating.md`](docs/evidence/S02E04-mechanical-scapegoating.md) — `THE ORDER`, повторено обвиняване на Mechanical и crisis scapegoating.
- [`docs/evidence/S02E04-mines-penal-labor.md`](docs/evidence/S02E04-mines-penal-labor.md) — metal extraction и penal labor system.
- [`docs/evidence/S02E04-salvador-quinn-meadows.md`](docs/evidence/S02E04-salvador-quinn-meadows.md) — Salvador Quinn, encoded letter и четиридневното изчезване на Meadows.
- [`docs/evidence/S02E04-vr-cleaner-technology.md`](docs/evidence/S02E04-vr-cleaner-technology.md) — immersive headset с Monteverde и връзката му с технологията на cleaner helmet.
- [`docs/evidence/S02E04-meadows-framing-sims.md`](docs/evidence/S02E04-meadows-framing-sims.md) — убийството на Meadows, framing на Mechanical и натискът на Sims.
- [`docs/evidence/S02E04-silo17-child-vault.md`](docs/evidence/S02E04-silo17-child-vault.md) — survivor-ът от Silo 17 като дете и vault continuity-refuge model.
- [`docs/evidence/S02E05-sims-judge-shadow.md`](docs/evidence/S02E05-sims-judge-shadow.md) — reassignment на Sims, Judge office и отделен shadow succession path.
- [`docs/evidence/S02E05-silo17-power-flooding-recovery.md`](docs/evidence/S02E05-silo17-power-flooding-recovery.md) — независимо IT захранване, саботаж на помпата на Level 144, наводняване и план за възстановяване.
- [`docs/evidence/S02E05-it-judicial-infrastructure-map.md`](docs/evidence/S02E05-it-judicial-infrastructure-map.md) — schematic lines, свързани с IT/Judicial, и hidden-backbone hypothesis.
- [`docs/evidence/S02E05-salvador-quinn-letter.md`](docs/evidence/S02E05-salvador-quinn-letter.md) — сканирано Quinn letter и encoded final payload.
- [`docs/evidence/S02E06-institutional-messaging.md`](docs/evidence/S02E06-institutional-messaging.md) — direct messaging, coexistence с courier и layered communication access.
- [`docs/evidence/S02E06-control-room-humint.md`](docs/evidence/S02E06-control-room-humint.md) — маршрутизирано полево/HUMINT докладване към оперативната картина в control room.
- [`docs/evidence/S02E06-radio-communications-control.md`](docs/evidence/S02E06-radio-communications-control.md) — Silo-wide radio cutoff capability на Bernard/IT.
- [`docs/evidence/S02E07-legacy-vault.md`](docs/evidence/S02E07-legacy-vault.md) — vault habitation, Legacy library и institutional-memory mechanism.
- [`docs/evidence/S02E07-352-year-chronology.md`](docs/evidence/S02E07-352-year-chronology.md) — 352-годишна възраст от construction и pre-Rebellion chronology refactor.
- [`docs/evidence/S02E07-anti-it-counter-narrative.md`](docs/evidence/S02E07-anti-it-counter-narrative.md) — handwritten anti-IT leaflet и competing crisis narrative.
- [`docs/evidence/S02E07-silo18-continuity-power.md`](docs/evidence/S02E07-silo18-continuity-power.md) — blackout-resilient IT power в Silo 18 и cross-Silo corroboration.
- [`docs/evidence/S02E08-quinn-historical-reset.md`](docs/evidence/S02E08-quinn-historical-reset.md) — историческото заличаване на Quinn, повтарящите се бунтове и обръщането на официалната история.
- [`docs/evidence/S02E08-memory-suppression-water.md`](docs/evidence/S02E08-memory-suppression-water.md) — хронично потискане на паметта чрез водата и потвърждение между епизоди.
- [`docs/evidence/S02E08-meadows-quinn-pact.md`](docs/evidence/S02E08-meadows-quinn-pact.md) — разследването на Meadows за семейството на Quinn и старо копие на `Pact Between the Founders`.
- [`docs/evidence/S02E08-quinn-decoded-message.md`](docs/evidence/S02E08-quinn-decoded-message.md) — декодираното съобщение на Quinn и формулировката `game is rigged` („играта е нагласена“).
- [`docs/evidence/S02E08-sims-ahundsen-message.md`](docs/evidence/S02E08-sims-ahundsen-message.md) — съобщението на R. Ahundsen до Judge Sims и контекстът с овощната градина.
- [`docs/evidence/S02E08-silo17-multiple-survivors.md`](docs/evidence/S02E08-silo17-multiple-survivors.md)
- [`docs/evidence/S02E09-quinn-safeguard-tunnel.md`](docs/evidence/S02E09-quinn-safeguard-tunnel.md) — Quinn: 50/51 Silos, safeguard и bottom-tunnel verification path.
- [`docs/evidence/S02E09-hidden-lower-contact.md`](docs/evidence/S02E09-hidden-lower-contact.md) — активният контакт в долната зона и предишните посетители Quinn/Meadows/George.
- [`docs/evidence/S02E09-silo17-vault-knowledge.md`](docs/evidence/S02E09-silo17-vault-knowledge.md) — среда за съхраняване на знание във vault-а на Silo 17.
- [`docs/evidence/S02E09-silo17-survivor-group.md`](docs/evidence/S02E09-silo17-survivor-group.md) — организираната група оцелели и обвинението `the killer` („убиецът“).
- [`docs/evidence/S02E09-coercive-message.md`](docs/evidence/S02E09-coercive-message.md) — принудителното цифрово съобщение със съпругата/камерата.
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

**Наблюдение → Правило → Evidence → Confidence → Отворени въпроси → Hypothesis**

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

S01E05 дава директно потвърден пример: Sims убива Trumbull → официалният разказ твърди самоубийство → Judge приключва случая.

Това не означава, че всички официални записи са неверни. Означава, че официалните записи се класифицират като institutional claims, когато няма независимо потвърждение.

### Допълнително правило след S01E06

**Загуба на публично знание ≠ пълна загуба на институционално знание.** Ограничената база данни за реликви показва, че избрани pre-Silo записи са запазени в привилегировани системи. Скритото наблюдение също вече е директно потвърдена инфраструктура, а не само извод от досието.

### Допълнително правило след S01E07

**Direct confession / direct observation > историческо обяснение.**

S01E07 съдържа както директно потвърдени механизми, така и исторически свидетелства. Например:
- измамата със запазения имплант е независимо потвърдена чрез физическото evidence от Allison + признанието на бащата на Juliette;
- потискането на паметта чрез водата и насочването срещу семейните линии на Flamekeepers остават исторически твърдения до независимо потвърждение;
- Flamekeepers не се приравняват автоматично с бунтовниците, докато evidence от епизода не установи връзката.

### Допълнително правило след S01E08

**Убеждение на персонаж може да бъде заменено от новонаблюдаван механизъм; институционално свидетелство само по себе си може да бъде принудителен механизъм.**

- По-ранното убеждение на Juliette, че баща ѝ е издал микроскопа, вече не е необходимо, след като mirror surveillance е известно и тя самата свързва двете.
- Твърдението Mayor/Sims „she wants to go out“ се следи отделно от това, което Juliette реално е казала; последвалият арест не прави твърдението ретроактивно вярно.

### Допълнително правило след S01E09

**Evidence, което става известно на персонаж, се следи отделно от evidence, вече известно на зрителя/проекта.**

Cleaning видеото на Jane Carmody вече беше директно визуално evidence в S01E01. S01E09 е важно, защото Juliette сама получава достъп до същото evidence; това не прави зеленото изображение изведнъж вярно и не решава дали е реално или манипулирано.

### Допълнително правило след S01E10

**Заключенията на персонажите остават отделни от директните системни разкрития.** Juliette първоначално заключава, че public display е лъжата, защото шлемът ѝ показва зелено изображение; S01E10 след това директно разкрива, че самото изображение в шлема е невярно. Затова ledger-ът пази нейното твърдение като извод на персонаж, а по-късното разкритие — като evidence от по-висок клас.

### Допълнително правило след S02E01

**Повторението между Silos укрепва hypotheses за стандартизация, а не автоматични изводи за централен контрол.** Когато същата архитектура се появява във втори Silo — камери в огледалата, IT, airlock, земеделие — можем по-силно да изведем общ дизайн/doctrine, но не заключаваме автоматично, че една активна централна власт контролира всеки Silo.

**Superseded inferences остават в history.** E188 запазва първоначалната погрешна Engineering/generator-target interpretation и я маркира като superseded, след като по-късен scene evidence идентифицира IT като действителната attacked/defended location.

### Допълнително правило след S02E02

**Привилегированата doctrine, вътрешната интерпретация и директният механизъм остават отделни evidence classes.** Заглавието в `THE ORDER` е директно институционално evidence; обясненията на Bernard/Meadows за лентата са вътрешни свидетелства; точният инженерен механизъм остава неустановен, докато не бъде директно установен.

**Повтарящата се защитена cross-Silo архитектура подкрепя стандартизация, а не идентично съдържание.** Подобните на vault IT помещения в два Silos засилват H38, без да приемаме, че съдържат едни и същи системи, хора или doctrine.

### Допълнително правило след S02E03

**Историческото потвърждение укрепва механизъм, без да превръща свидетелството в обективна телеметрия.** Silo 17 силно съвпада с `THE ORDER`, но действията на Ron, времето на праха/отровата и заповедите на Russell остават свидетелство на оцелял, освен ако не бъдат независимо наблюдавани.

**Chronology contradictions се запазват, а не се нормализират насила.** `SILO YEAR 96/97`, `116 A.R.` и приблизителното твърдение на Bernard за Jane Carmody „~200 years“ се пазят като отделни anchors, докато consistent mapping не бъде директно подкрепен.

### Допълнително правило след S02E04

**Кризисният разказ може сам по себе си да е проектиран механизъм.** Когато doctrine предписва виновник и ръководството инсценира събития, които да подкрепят този разказ, публичното обвинение е evidence за управленско поведение, а не evidence, че обвинената група е причинила кризата.

**Вътрешният конфликт в елита се следи отделно от формалната йерархия.** Класифицираният достъп на Bernard и политическото/оперативното влияние на Sims могат да съществуват едновременно; нито един не се приема като пълен контрол над другия без evidence за конкретния домейн.

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

Институции, закони, забрани, йерархия, прилагане, наказание, разследване и реално срещу формално разпределение на властта.

### Информационна система

Достъп, наблюдение, досиета, забранено знание, архиви, историческа памет, комуникации, образование и възможно манипулиране на информация.

### Capability-control system

Какво жителите физически могат да правят/наблюдават: вертикално движение, радиостанции, увеличение, достъп до ограничени пространства и инструменти за независимо откриване.

### Социална система

Population, reproduction, profession, level structure, social mobility, trust, fear, norms и inter-level relations.

### Material/resource system

Ownership, assignment, recycling, redistribution, scarcity и closed-loop use на durable goods.

### Система за оцеляване

Разделяме правилата, които реално може да са необходими за оцеляване, от правилата, които може да служат за институционален контрол.

### Модел на външния свят

**това, в което героите вярват ≠ това, което властите твърдят ≠ това, което показва екранът ≠ това, което е обективно установено**

След S01E05 публичният екран има нормални дневни/нощни състояния, систематично времево поведение на небесните обекти и необичайно зелено състояние при изключване на захранването.

## Evidence класове

- **Direct observation** — сериалът директно показва събитието/обекта.
- **Repeated observation** — поведението/моделът се появява независимо повече от веднъж.
- **Character testimony** — доказва какво твърди/вярва герой, не непременно че твърдението е вярно.
- **Institutional claim** — официално правило, исторически разказ или заключение по дело; третира се като claim до независимо потвърждение.
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

**Кандидат → Активна → Засилена → Отслабена → Преработена → Отхвърлена → Потвърдена**

`Confirmed` се използва пестеливо.

Ако нова информация опровергава само част от theory, предпочитаме **refactor**, вместо да я защитаваме на всяка цена.


### Допълнително правило след S02E05

**Формалната длъжност и скритото наследяване са отделни evidence layers.** Това, че Bernard назначава Sims за Judge, но му отказва ролята `shadow`, показва, че публичният институционален ранг не означава автоматично достъп до най-дълбокия IT succession/read-in path.

**Чертежите с инфраструктурни линии не се интерпретират сами.** Линия, стигаща до IT или Judicial, се записва като връзка/път на схемата; интерпретациите за захранване, данни, комуникации, контрол и utility остават конкуриращи се, докато диаграма или диалог не идентифицира услугата.



### Допълнително правило след S02E06

**Съществуване на технология ≠ универсален достъп до нея.** Direct messaging на институционални терминали доказва, че Silo има способност за digital комуникация, но не доказва, че обикновените жители имат равен достъп до крайни точки/акаунти.

**Комуникационните канали се моделират отделно според достъпа и контрола.** Куриерите, цифровите съобщения и радиото могат да съществуват паралелно, защото обслужват различни групи/функции. Способността на IT да прекъсва радиото е evidence за контрол върху този канал, а не автоматично доказателство, че IT чете всяко цифрово съобщение или контролира всяка физическа комуникация.

**Почти реалновремевото полево докладване ≠ директно доказателство за изходния терминал.** Докладът в control room установява цифров HUMINT/полеви канал за докладване, но изходното устройство, посредникът и протоколът остават неустановени.



### Допълнително правило след S02E07

**Защитено съхраняване на знание ≠ публична историческа приемственост.** Библиотеката `Legacy` показва, че привилегировано историческо/техническо знание може да бъде умишлено запазено, докато обикновените жители губят или нямат достъп до широк исторически контекст.

**Функционална резервираност ≠ идентична архитектура на източника.** Това, че IT в Silo 18 остава захранен при blackout, доказва резервно/continuity power, но само по себе си не доказва същия външен източник, описан за Silo 17.

**Разпространявано съобщение ≠ проверено авторство или истина.** Anti-IT листовката е директно evidence, че съществува контраразказ. Нейните твърдения, автор, разпространител и официална подкрепа от Mechanical се следят отделно.

**Изведената хронология запазва приблизителността.** `352 years since construction - ~140 years since Rebellion ≈ 212 pre-Rebellion years` е силен изведен ориентир, но приблизителните входни свидетелства не се превръщат мълчаливо в точни календарни дати.



### Допълнително правило след S02E08

**Привилегированото историческо свидетелство може да отхвърли официалния разказ, без автоматично да се превръща във всезнаеща истина.** Bernard директно идентифицира публичния разказ за Quinn като неверен и дава последователен скрит механизъм, но мотивите на Quinn и причинното твърдение, че самата историческа памет е пораждала бунтове, остават проследявани като привилегировано историческо свидетелство.

**Потвърден механизъм ≠ идентично вещество.** Свидетелството за паметта и водата в S01E07 + разказът на Bernard в S02E08 силно установяват историческо потискане на паметта чрез водата, докато S02E03 доказва, че съществува текущо лекарство за забравяне. Точната идентичност на съединението между различните ери остава неустановена.

**Историческото заличаване и историческото съхраняване могат да съществуват едновременно по дизайн.** Публичните записи/книги/памет могат да бъдат потискани, докато `Legacy` и други привилегировани системи пазят избрана истина. Моделът е контролиран достъп, а не пълно унищожение.

**Свързване със стар документ ≠ авторство.** Ръкописното `Salvador Quinn` върху `The Pact Between the Founders` го асоциира директно с това копие, но не установява, че е автор на Pact, че е Основател или че е променял текста му.

**Декодирана фраза ≠ декодирана система.** `the game is rigged` („играта е нагласена“) е директно evidence от съобщението на Quinn, но точният референт на `the game` остава отворен.


## Текущ модел за външния свят

След S02E08 основната визуална неяснота за външната среда остава разрешена. S02E08 не променя съществено модела за външната опасност; директно променя модела за обитаване на Silo 17, като потвърждава множество живи обитатели:

1. **Зелената гледка за cleaner-а е невярна** — шлемът показва манипулиран / подобен на overlay визуален слой.
2. **Безплодната външна среда е в значителна степен реална** — след отпадането на невярния слой Juliette вижда опустошен терен.
3. **Съществуват множество Silo инсталации**; оцелял от Silo 17 заявява точен брой на системата **50**.
4. В далечината се вижда **ruined / city-like skyline**, но identity/location не са установени.
5. Juliette директно достига и влиза във **втори Silo**.
6. Голямо поле от масови човешки останки около този Silo потвърждава реална смъртоносна външна опасност при наблюдаваните условия.
7. Текущият най-подходящ клас на опасността е **подвижна въздушна/прахова опасност**, чиято локална концентрация може временно да се разсее и после да се върне; точният механизъм токсин/патоген/частици остава неустановен.
8. Уплътняването на костюма и целостта на системата за дишане влияят съществено върху оцеляването.
9. Insider dialogue силно свързва оцеляването на Juliette със замяната на normal cleaning tape с по-добър seal.
10. Bernard/IT получава live exterior video, свързано с Juliette, докато тя е навън.
11. Silo 17 показва, че ако expected death на cleaner не бъде наблюдавана, може да възникне belief „outside is safe“ и mass-exit cascade.
12. Juliette изрично идентифицира повтарящата се зелена визуална последователност като поведенчески trigger за cleaning.
13. Bernard демонстрира standalone immersive headset с preserved pre-Silo natural environment и обяснява, че работи подобно на cleaner-helmet imagery.
14. S02E08 директно потвърждава множество живи обитатели в Silo 17 отвъд познатия досега оцелял от IT vault-а.

Все още остават неустановени точната технология за рендиране в шлема, точният смъртоносен външен агент, точният път на теча в костюма, точният източник/формат на live feed-а от cleaner-а, независимото потвърждение на броя 50 Silos, пълната схема за номериране на Silos, евентуална текуща централна власт и идентичността на далечния skyline.

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
LEVEL 1 / UP-TOP
        │
        ├─ Sheriff's Department / holding
        ├─ Cell 3
        └─ cleaning airlock opposite Cell 3
        │
        ▼
LEVEL 8 → 9 → 12 → ~14 JUDICIAL → 17 → 23 → 26 → 27 → 29 → 30 → 50 → 55 → 67 → 87
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

Въпросителните означават силен пространствен извод или неустановена връзка, а не директно потвърждение от един кадър.

## Workflow след всеки епизод

1. Записваме новите observations.
2. Отделяме facts от character/institutional claims.
3. Добавяме visual evidence.
4. Проверяваме recurring patterns.
5. Актуализираме rules и active hypotheses.
6. Променяме confidence само с конкретна причина.
7. Записваме contradictions.
8. Добавяме open questions.
9. Определяме какво би опровергало важните теории.
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
analysis/S02E09-hidden-lower-system
analysis/S02E10-safeguard-presilo-washington
analysis/S03E01-memory-control-supervisory-system
analysis/S03E02-memory-retrieval-population-control
analysis/S03E03-safeguard-isolation-deception
analysis/S03E04-covert-network-abyss-bernard
hypothesis/<name>
model/<name>
methodology/<change>
```

Историята в Git е част от разследването: трябва да можем да видим кога е възникнала една теория, кое evidence я е укрепило, кое я е отслабило и кога е била преработена или отхвърлена.

---

**Следваща knowledge boundary:** `S03E05`
