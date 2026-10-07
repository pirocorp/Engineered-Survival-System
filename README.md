# Проект SILO — обратен инженеринг на Engineered Survival System

Дневник за систематичен, основан на доказателства и дисциплиниран спрямо спойлери анализ на телевизионния сериал **Silo**.

Целта е да третираме света на сериала като **черна кутия**: наблюдаваме поведението на системата, извличаме възможни правила, изграждаме конкуриращи се хипотези и ги променяме или отхвърляме, когато нови епизоди дадат по-добри доказателства.

> **След S03E10 Silo 1 е директно установен като централен надзорен възел за оперативна непрекъснатост с метаболитна/криогенна стаза, работещ асансьор, централно контролно помещение и управлявана от човек роля на „Гласът“. Victor е показан като човешкия оператор зад „Гласът“, а сенаторът е директор на Silo 1; възможна ИИ/автоматизирана подсистема остава неизяснена. Safeguard има локално прекъсваемо вътрешно подаване на отровна смес и външен резервен механизъм с дрон, способен на отровно и кинетично въздействие. Пактът и Директивата са отделни управленски слоеве, Вторият трезор на Silo 18 е защитена надзорна зона, а Helen Drew е идентифицирана като журналистката от периода преди силозите. Механизмът на опасността във външната среда остава неизяснен: моделът за повсеместно смъртоносен външен въздух е отхвърлен, но и твърдението `outside is safe` („навън е безопасно“) не е установено.**

## Език на проекта

Основният език на хранилището е **български**.

Всички обяснителни текстове, анализи, заключения, въпроси и описания се пишат на български. Английски се запазва само когато е необходим за точност: при дословен цитат, оригинален надпис от интерфейс или документ, име на файл или път, име на Git клон или PR, програмен идентификатор, утвърдена абревиатура или собствено име.

### Задължително езиково правило

**Аналитичната и обяснителната проза в хранилището се пише на български.**

Английски могат да останат само:
- точни цитати от сериала;
- оригинални надписи от интерфейс или документ, например `THE ORDER`, `DIRECT MESSAGING`, `SERVER ROOM`, `Legacy`;
- имена на файлове, пътища, Git клонове, PR-и и програмни идентификатори;
- утвърдени абревиатури и собствени имена.

**Английска аналитична или обяснителна проза не се използва.**

## Граница на знанието

**Текуща граница на знанието:** **S03E10**

**Статус на гледане:** **Сезон 3 — S03E10 завършен / сезон 3 е завършен**

Не се използва никаква информация след S03E10, книги, уикита, интервюта, бъдещи синопсиси, изтичания или ретроспективни обяснения.

## Текущо състояние

След S03E10 най-силният работен модел е:

> **Silo 1 е централен надзорен възел за оперативна непрекъснатост с персонал от епохата на основаването в метаболитна/криогенна стаза, работещ асансьор, централно контролно помещение и управлявана от човек роля на „Гласът“. Victor е директно показан като оператор зад „Гласът“, а сенаторът е директор на Silo 1. Възможна ИИ/автоматизирана подсистема остава неизяснена. Safeguard разполага с локално прекъсваемо вътрешно подаване на отровна смес и външен резервен механизъм с дрон, способен на отровно и кинетично въздействие. Пактът и Директивата са отделни управленски слоеве. Вторият трезор на Silo 18 е защитена надзорна зона. Helen Drew е идентифицирана като журналистката от периода преди силозите. Механизмът на опасността във външната среда остава неизяснен: моделът за повсеместно и моментално смъртоносен външен въздух е отхвърлен, но и твърдението „навън е безопасно“ не е установено.**

### S03E10 — Silo 1, „Гласът“, стазата и Safeguard

- Daniel Keen е периодично събуждан от метаболитна/криогенна стаза в Silo 1; по-късен изрично посочен интервал между събужданията е **5 години**.
- Silo 1 съдържа голямо съоръжение за стаза, вграден работещ асансьор и централно контролно/оперативно помещение.
- Сенаторът от групата от епохата на основаването е директор на Silo 1 и също участва в цикъла на стаза.
- Victor е директно показан като човешки оператор зад „Гласът“. Това установява човешка операторска роля, но не изключва възможна автоматизирана или ИИ подсистема.
- Медицинският доклад след реанимация описва объркване, когнитивно забавяне и физиологични ефекти, но не обяснява напълно избирателните автобиографични пропуски в паметта на Daniel.
- Криптираното съобщение на Victor идентифицира **Helen Drew** като журналистката, която Daniel помни само фрагментарно.
- Неуспешният Safeguard в Silo 17 е свързан с отровна смес, която не достига целта заради блокирана тръба. Исторически и други силози са правили същия тип локално прекъсване.
- Silo 1 разполага с дрон за въздушно наблюдение, около **30 L** товар от смес и **2000 патрона**.
- След масовото излизане от Silo 17 Daniel нарежда външно смъртоносно ограничаване; заявената причина е предотвратяване на междусилозно „замърсяване“.
- Прекият диалог разделя **Пакта** от **Директивата**: Пактът може да престане да важи за хората, които са напуснали, докато Директивата продължава да определя действията по изолация.
- Silo 18 блокира собствената си тръба на Safeguard; Silo 1 засича блокирането, поставя наблюдение с дрон и издава заповед за убийство при неразрешено излизане.
- Juliette поддържа междусилозна комуникация със Silo 17.
- Долната структура е назована **Вторият трезор на Silo 18**.
- Daniel предлага Safeguard да не бъде използван, ако Silo 18 прекрати разследването на Втория трезор и междусилозния контакт.
- Juliette приема сделката, но след това предлага тайна подготовка за изненадващ удар/превземане на Silo 1.
- Опасността във външната среда остава неизяснена. Отровното/дроновото налагане от Silo 1 е потвърдено, но твърдението „навън е безопасно“ не е установено.

### S03E09 — Пактът, 50-те силоза и външната среда

- Bernard оспорва „Гласът“, иска Juliette да бъде освободена и дозирането с Vitamin D+ да бъде спряно.
- „Гласът“ предпочита Bernard да бъде формално обвинен и изпратен на почистване, а Vitamin D+ да продължи.
- Bernard допуска, че зад интерфейса на „Гласът“ стоят човешки оператори в Silo 1; към края на S03E09 това все още е хипотеза на персонаж.
- Bernard и Juliette са предназначени за почистване без костюми.
- Bernard излиза без костюм, остава жив за кратък период и умира. Следователно смъртоносният резултат навън не изисква задължително стандартен костюм.
- Резултатът при отворения шлюз на Silo 17 остава силно противоречие срещу прост модел за моментална смърт само от външния въздух.
- Минният асансьор е пряко нарушение на общата забрана за механизиран транспорт; епизодът допълнително потвърждава асансьорите като изрично забранена подкатегория.
- Пактът е описан като правилник за приблизително 500 години подземен живот.
- Пактът е първоначално създаден с помощта на ИИ, а сестрата на Daniel Keen и лекарят го редактират. Това **не** означава автоматично, че „Гласът“ е ИИ.
- При хоризонт от 500 години и ориентир от 352 години от строителството се получават приблизително 148 години като чиста аритметика; това не е установена дата за освобождаване.
- Картата при откриването и въздушното физическо разположение потвърждават **Silo 1 + 7 × 7 = 50 силоза**.
- Историческото твърдение на Bernard за '51' остава необяснено; Silo 1 е част от официалните 50.
- Daniel Keen е разпределен към **Silo 1**, а журналистката — към **Silo 18**.
- Първоначалният прием използва маршрутизиране по номера, лицево разпознаване и RF чипове в служебните значки.
- Милиардерът/спонсорът на проекта е идентифициран като **Per Stenson**.
- Съобщението 'sit still and be patient' предизвиква осезаема реакция у Daniel; интерпретацията му като кодирано предупреждение остава хипотеза.
- По време на откриването/приема се случва ядрена детонация, докато хора все още са на повърхността. Извършителят и предварителното знание не са установени.

### S03E08 — топология, нанотехнологии и иранският обект

- Kyle е пряко потвърден жив след стрелбата във външната среда; 'neutralized' не може да се чете автоматично като „мъртъв“.
- Silo 17 е показан с едновременно отворени врати на шлюза без непосредствена масова смърт. Това отслабва модела за еднакво и моментално смъртоносна външна среда.
- „Гласът“ получава актуализация за външната среда от въздушно наблюдение; телата на Kyle и Kennedy вече не са на мястото.
- Silo 17 възстановява радиовръзка и комуникира кодирано със Silo 18.
- Официалната топология е **Silo 1 + 7 × 7 = 50 силоза**; историческото '51' на Bernard остава отделно противоречие.
- Схемата на Safeguard показва **7 главни линии от Silo 1 → 7 групи → локални разклонения към всеки силоз**.
- Първоначалният строителен план е 10 изкопни машини × 5 силоза. Keen обяснява, че изваждането на машините струва повече от оставянето им заровени.
- Първоначалната цел на проекта е оцеляване на хора и последващо повторно заселване след неизбежна катастрофа, свързана с нанотехнологии.
- По-ранната линия за „мръсна бомба“ е уточнена като атака с нанооръжие, целяща да забави американските програми за ИИ и нанотехнологии. Отговорността на Iran остава ограничено установена.
- Нанооръжието поема управлението на самолета за секунди; аналоговата модернизация е била защитна мярка срещу тази заплаха.
- Малък ядрен заряд е детониран под иранското съоръжение за нанооръжия. Зарядът е поставен чрез таен подземен тунел с дължина около **120 km**.
- Журналистката обвинява ръководството, че въздушният екип е използван като експеримент за измерване на възможностите на вражеската нанотехнология. Това остава нейно обвинение, а не независимо установен факт.
- Комплексът от силози е приблизително **50 km от Atlanta**. Разрушеният градски силует = Atlanta остава силен извод, но не е изрично означен.
- Bernard признава, че е отровил Meadows, защото му е било казано, че това е необходимо, за да не загине целият Силоз; по-късно обещава да спре „тази тирания“.
- В края на епизода Juliette е заключена заедно с Robert Sims.

### S03E07 — междусилозният контакт и ограниченото знание на „Гласът“

- Lukas Kyle и Patrick Kennedy тръгват към Silo 17 с мисия за прехвърляне на дете и тайна цел за противодействие на Safeguard.
- Във външната последователност се чува жужене, после кратък звук, наподобяващ оръжие, а по-късно „Гласът“ докладва 'neutralized'. Точният механизъм на неутрализирането остава неизвестен.
- Радиовръзка, представена като Kyle/Kennedy, влиза в противоречие с разказа на „Гласът“/Camille и прекъсва непосредствената операция на Judicial около тръбата на Safeguard в Silo 18.
- „Гласът“ извежда поражението на Safeguard в Silo 17 от записа и наблюдаваните резултати и прави извод за намеренията на Juliette. Това подкрепя модел за ограничено, а не всезнаещо знание.
- Твърдението „Safeguard е непобедим“ е в напрежение с практическото му временно преодоляване в Silo 17; резервираност или резервен механизъм остават хипотеза.
- Конзолата показва 'Live feed replaced with null visual. Looping static image.', което директно потвърждава възможност за подмяна на видеопотока.
- Реалното нощно небе навън показва ясни звезди и дава ориентир за сравнение с по-ранните звездоподобни модели на публичния екран.
- Сестрата на Daniel Keen има фрагментирани спомени и подаден автобиографичен разказ; тя е под NDA, а Keen трябва да подпише преди пълния инструктаж.
- Строителната програма за силозите е директно показана в Georgia, близо до Atlanta, като мащабна строителна площадка с множество съоръжения.

### Сезони 1–2 — основни установени механизми

- Зелената гледка при почистване е повторяема при Allison, Jane Carmody и Holston.
- Публичният екран обичайно показва безплодната външна среда.
- При изключването на захранването в S01E03 самият публичен екран показва зелено състояние; S01E04 показва нормално нощно състояние.
- S01E05 показва системно и зависимо от времето движение на звездоподобни светлини на нощния екран. Наблюдателят в кафетерията не познава понятието „звезди“ и сам възстановява модели на движение.
- Силозът има **144 нива**, а Bernard заявява **10 112 жители**.
- Пактът умишлено забранява механизиран транспорт и увеличителни устройства над определен праг.
- Досието на Juliette съдържа информация от разговор с Holston, което е силно доказателство за скрито наблюдение/докладване.
- Douglas Trumbull е хванат да манипулира/подхвърля доказателства и се опитва да убие Juliette.
- Sims лично убива Trumbull и после представя смъртта му като самоубийство. Следователно официалният институционален запис не може автоматично да се приема като независимо установена истина.
- Juliette търси формално основание за повторно отваряне на случая George и взема PEZ реликвата от зоната под Силоза.
- 'The Syndrome' е изричен термин в света на сериала. Новият заместник-шериф е конкретен засегнат персонаж, но природата и причината остават неизвестни.
- Няма установена връзка 'The Syndrome ↔ забрана за увеличение'; това остава спекулация с много ниска увереност.
- Централизиран център за наблюдение с множество видеопотоци следи множество вътрешни места, включително дома на Juliette.
- Ограничена база данни за реликви на Judicial пази архивни записи 'PRE-SILO', а Sims/Judicial има привилегирован достъп.
- Пътеводителят за Georgia първоначално установява само географска връзка с американския щат; S03E07 по-късно директно показва строителната площадка на силозите в Georgia, близо до Atlanta.
- Sims оперативно ръководи наблюдението. Judge Meadows и медицинският център също са наблюдавани.
- Скритите камери са потвърдени зад/в огледалата, а достъпът до контролния център минава през скрит маршрут през помещение на Janitorial.
- Flamekeepers са описани като група, съхраняваща история и реликви. Точната им връзка с Бунта остава неустановена.
- Историческото свидетелство въвежда потискане на паметта чрез водата още преди/около епохата на Бунта.
- Бащата на Juliette признава измамата с контрацептивните импланти, което потвърждава скрит механизъм за репродуктивен контрол.
- Juliette и George са свързани чрез своите майки Flamekeepers и междупоколенческа мрежа за съхраняване на знание.
- Майката на Juliette използва самоделно микроскопско/увеличително устройство за независимо медицинско изследване; ограничените записи показват институционално внимание към тази дейност.
- Juliette осъзнава, че наблюдението чрез огледалата може да обясни откриването на микроскопа на майка ѝ, без да е необходимо баща ѝ да е бил информатор.
- Приоритетно съобщение от Medical до Martha Walker директно потвърждава структурирани цифрови съобщения между отдели.
- Кметът и Sims координират капан и твърдят, че Juliette е казала, че иска да излезе навън; тя е арестувана на тази основа.
- S01E09 потвърждава, че Juliette оцелява след падането върху междинен мост на ниво 23.
- Малък осветен предмет с номер **18** е показан при Bernard; по-късно е установено, че е физически ключ.
- Juliette отваря 'JANE CARMODY CLEANING', което прави алтернативното зелено изображение част и от нейното собствено знание.
- S01E10 директно разкрива, че зелената гледка в шлема е невярна. Безплодната външна среда остава видима след отпадането на фалшивия слой.
- Различната лента/материал в костюма на Juliette съществено влияе на оцеляването ѝ.
- Широките външни кадри разкриват множество силозни инсталации и далечен разрушен/градоподобен силует.
- Дъното около ниво 144 съдържа голяма вентилационна/въздухообработваща инфраструктура.
- S02E01 директно поставя Juliette във втори Силоз и превръща системата от множество силози от външно наблюдение в пряко изследване.
- Историческата последователност във втория Силоз показва графити срещу Основателите/измамата, въоръжено настъпление към IT, пробив на шлюза и масово излизане.
- Голямото поле с човешки останки около втория Силоз потвърждава реална смъртоносна опасност във външната среда при наблюдаваните условия.
- Вторият Силоз съдържа същата концепция за скрити камери в огледалата, което силно подкрепя стандартизиран междусилозен дизайн.
- IT във втория Силоз е защитена стратегическа зона с прекъснат достъп, локално осветление и отделение, подобно на трезор.
- S02E02 въвежда 'THE ORDER' и правилото 'IN THE EVENT OF A FAILED CLEANING, PREPARE FOR WAR'.
- S02E03 исторически потвърждава механизма чрез Silo 17: отказът на Ron да почисти е последван от бунт и масово излизане.
- S02E03 въвежда формалния медицински протокол 'CODE SILO ORANGE', който изисква контрацепцията да остане, докато пациентът вярва, че е премахната.
- S02E04 показва, че 'THE ORDER' предписва Mechanical да бъде обвиняван при криза; Bernard впоследствие използва същия принцип за натопяване.
- S02E05 установява независимо резервно електрозахранване на IT в Silo 17 и възможност то да захрани критична инфраструктура за възстановяване.
- S02E06 показва институционални директни съобщения, полеви цифрови доклади и способност на IT да прекъсва радиокомуникациите.
- S02E07 показва жилищни помещения в IT трезора и библиотеката/архива **Legacy**, както и възрастов ориентир от **352 години** за Силоза.
- S02E08 разкрива умишленото историческо заличаване на Salvador Quinn: прекъсване на публичния достъп до историята, конфискуване на книги и продължително потискане на паметта чрез водата.
- S02E09 разкрива физическия долен тунел и активния скрит контакт; преди Lukas до тази точка са достигали само Salvador Quinn, Mary Meadows и George Wilkins.
- S02E10 превръща Safeguard от абстрактна заплаха в конкретна система за унищожаване на населението на цял Силоз и показва физически път за подаване на смъртоносната смес около ниво 14.
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
- [`docs/episodes/S03E05.md`](docs/episodes/S03E05.md) — episode record за S03E05.
- [`docs/episodes/S03E06.md`](docs/episodes/S03E06.md) — episode record за S03E06.
- [`docs/episodes/S03E10.md`](docs/episodes/S03E10.md) — Season 3 finale record за S03E10.
- [`docs/evidence/S03E10-silo1-stasis-memory.md`](docs/evidence/S03E10-silo1-stasis-memory.md) — Silo 1 stasis, post-reanimation, memory и founding-era continuity.
- [`docs/evidence/S03E10-safeguard-drone-directive.md`](docs/evidence/S03E10-safeguard-drone-directive.md) — Safeguard failure modes, drones, Pact/Directive и external containment.
- [`docs/evidence/S03E10-voice-control-room-victor-camille.md`](docs/evidence/S03E10-voice-control-room-victor-camille.md) — central control room, human Voice operator, Victor/Camille.
- [`docs/evidence/S03E10-second-vault-daniel-juliette.md`](docs/evidence/S03E10-second-vault-daniel-juliette.md) — Second Vault, междусилозен контакт и Daniel–Juliette deal.
- [`assets/S03E10/MANIFEST.md`](assets/S03E10/MANIFEST.md) — S03E10 visual evidence manifest / validated Git blobs.
- [`docs/audits/S03-consistency-audit.md`](docs/audits/S03-consistency-audit.md) — post-Season-3 methodology / consistency audit.
- [`docs/episodes/S03E09.md`](docs/episodes/S03E09.md) — episode record за S03E09.
- [`docs/evidence/S03E09-voice-bernard-cleaning.md`](docs/evidence/S03E09-voice-bernard-cleaning.md) — Bernard, „Гласът“, cleaning decision и human-operator hypothesis.
- [`docs/evidence/S03E09-exterior-mines-pact.md`](docs/evidence/S03E09-exterior-mines-pact.md) — no-suit exterior outcome, Silo 17 contradiction, mines/elevator и Pact origin.
- [`docs/evidence/S03E09-opening-topology-intake.md`](docs/evidence/S03E09-opening-topology-intake.md) — opening-day physical topology, assignments, intake и catastrophe transition.
- [`assets/S03E09/MANIFEST.md`](assets/S03E09/MANIFEST.md) — S03E09 visual evidence manifest.
- [`docs/episodes/S03E08.md`](docs/episodes/S03E08.md) — episode record за S03E08.
- [`docs/evidence/S03E08-exterior-bernard.md`](docs/evidence/S03E08-exterior-bernard.md) — опасността във външната среда, Silo 17 и Bernard alignment.
- [`docs/evidence/S03E08-presilo-nanotechnology-iran.md`](docs/evidence/S03E08-presilo-nanotechnology-iran.md) — original mission, nanotechnology threat и Iran operation.
- [`docs/evidence/S03E08-silo-topology-safeguard.md`](docs/evidence/S03E08-silo-topology-safeguard.md) — 50-Silo topology, safeguard routing и digger lifecycle.
- [`assets/S03E08/MANIFEST.md`](assets/S03E08/MANIFEST.md) — S03E08 visual evidence manifest.
- [`docs/episodes/S03E07.md`](docs/episodes/S03E07.md) — episode record за S03E07.
- [`docs/evidence/S03E07-exterior-voice-safeguard.md`](docs/evidence/S03E07-exterior-voice-safeguard.md) — Kyle/Kennedy, exterior reach, safeguard contradiction и radio conflict.
- [`docs/evidence/S03E07-presilo-georgia-memory.md`](docs/evidence/S03E07-presilo-georgia-memory.md) — sister fragmented memory, NDA/read-in и Georgia/Atlanta Silo construction.
- [`docs/evidence/S03E07-console-feed-control.md`](docs/evidence/S03E07-console-feed-control.md) — low-level console, reboot и null-feed static loop.
- [`assets/S03E07/MANIFEST.md`](assets/S03E07/MANIFEST.md) — S03E07 visual evidence manifest.
- [`docs/evidence/S03E06-silo1-power-safeguard.md`](docs/evidence/S03E06-silo1-power-safeguard.md) — Silo 1 external IT power и separate safeguard route.
- [`docs/evidence/S03E06-juliette-voice-memory.md`](docs/evidence/S03E06-juliette-voice-memory.md) — Juliette, Camille, „Гласът“ и selective disclosure.
- [`docs/evidence/S03E06-vitamin-d-water.md`](docs/evidence/S03E06-vitamin-d-water.md) — active Vitamin D+ water deployment.
- [`docs/evidence/S03E06-presilo-iran-takeover.md`](docs/evidence/S03E06-presilo-iran-takeover.md) — car↔aircraft external-control linkage и Iran attribution doubt.
- [`assets/S03E06/MANIFEST.md`](assets/S03E06/MANIFEST.md) — S03E06 visual evidence manifest.
- [`docs/evidence/S03E05-sims-voice-safeguard.md`](docs/evidence/S03E05-sims-voice-safeguard.md) — Camille/Robert, „Гласът“, safeguard hierarchy и lethal threat cluster.
- [`docs/evidence/S03E05-bernard-fake-death-robert-network.md`](docs/evidence/S03E05-bernard-fake-death-robert-network.md) — Bernard fake death, Mechanical alliance и Robert counter-line.
- [`docs/evidence/S03E05-memory-relic-radio.md`](docs/evidence/S03E05-memory-relic-radio.md) — relic-triggered memory retrieval, The Order policy, radio isolation и Silo 1 monitoring.
- [`docs/evidence/S03E05-presilo-ai-iran-vehicle.md`](docs/evidence/S03E05-presilo-ai-iran-vehicle.md) — AI/clinic/Iran convergence и vehicle takeover.
- [`assets/S03E05/MANIFEST.md`](assets/S03E05/MANIFEST.md) — S03E05 visual evidence manifest.
- [`docs/evidence/S03E04-memory-escape-network.md`](docs/evidence/S03E04-memory-escape-network.md) — pill substitution, nurse intervention и covert escape/support chain.
- [`docs/evidence/S03E04-presilo-cooptation-pentagon.md`](docs/evidence/S03E04-presilo-cooptation-pentagon.md) — Keen/journalist evasion, co-optation offers и Pentagon callback.
- [`docs/evidence/S03E04-deep-route-bernard.md`](docs/evidence/S03E04-deep-route-bernard.md) — concealed abyss route и Bernard alive correction.
- [`assets/S03E04/MANIFEST.md`](assets/S03E04/MANIFEST.md) — S03E04 visual evidence manifest.
- [`docs/evidence-ledger.md`](docs/evidence-ledger.md) — evidence регистър с confidence и epistemic class.
- [`docs/evidence/S01E01-exterior-visual-contradiction.md`](docs/evidence/S01E01-exterior-visual-contradiction.md) — focused exterior evidence след S01E01.
- [`docs/evidence/S01E02-holston-visual-split.md`](docs/evidence/S01E02-holston-visual-split.md) — simultaneous cleaner/public visual split при Holston.
- [`docs/evidence/S01E02-sub-silo-construction-layer.md`](docs/evidence/S01E02-sub-silo-construction-layer.md) — hidden construction layer под Silo.
- [`docs/evidence/S01E03-public-display-powerdown-flash.md`](docs/evidence/S01E03-public-display-powerdown-flash.md) — lush state на публичният екран при power-down.
- [`docs/evidence/S01E04-sheriff-succession-and-control.md`](docs/evidence/S01E04-sheriff-succession-and-control.md) — Judicial/IT opposition и Sheriff succession conflict.
- [`docs/evidence/S01E05-surveillance-trumbull-coverup.md`](docs/evidence/S01E05-surveillance-trumbull-coverup.md) — surveillance, framing, Trumbull и false suicide narrative.
- [`docs/evidence/S01E05-celestial-observation.md`](docs/evidence/S01E05-celestial-observation.md) — star-like temporal behavior и lost astronomical knowledge.
- [`docs/evidence/S01E05-pact-capability-restrictions.md`](docs/evidence/S01E05-pact-capability-restrictions.md) — mechanized-transport и magnification restrictions.
- [`docs/evidence/S01E06-centralized-surveillance.md`](docs/evidence/S01E06-centralized-surveillance.md) — директно потвърдено централизирано вътрешно наблюдение.
- [`docs/evidence/S01E06-relic-database-pre-silo.md`](docs/evidence/S01E06-relic-database-pre-silo.md) — PEZ lookup, Judicial relic DB и preserved pre-Silo knowledge.
- [`docs/evidence/S01E06-georgia-relic.md`](docs/evidence/S01E06-georgia-relic.md) — pre-Silo geographic clue за Georgia, USA.
- [`docs/evidence/S01E07-surveillance-command-and-mirrors.md`](docs/evidence/S01E07-surveillance-command-and-mirrors.md) — Sims command, mirror cameras и concealed surveillance architecture.
- [`docs/evidence/S01E07-flamekeepers-memory-erasure.md`](docs/evidence/S01E07-flamekeepers-memory-erasure.md) — Flamekeepers, relic preservation и water-memory claim.
- [`docs/evidence/S01E07-reproductive-control.md`](docs/evidence/S01E07-reproductive-control.md) — doctor confession и reproductive-control mechanism.
- [`docs/evidence/S01E07-flamekeeper-family-network.md`](docs/evidence/S01E07-flamekeeper-family-network.md) — intergenerational Flamekeeper връзка между Juliette и George.
- [`docs/evidence/S01E08-illicit-microscopy-and-mirror-surveillance.md`](docs/evidence/S01E08-illicit-microscopy-and-mirror-surveillance.md) — microscope, restricted record и revision на бащата като информатор model.
- [`docs/evidence/S01E08-fabricated-cleaning-trigger.md`](docs/evidence/S01E08-fabricated-cleaning-trigger.md) — Mayor/Sims trap, disputed exit claim и arrest.
- [`docs/evidence/S01E08-bernard-judge-power.md`](docs/evidence/S01E08-bernard-judge-power.md) — Bernard’s claim за Judge Meadows и hidden hierarchy candidate.
- [`docs/evidence/S01E09-level23-escape.md`](docs/evidence/S01E09-level23-escape.md) — приземяване върху bridge на Level 23 и резултат от escape-а.
- [`docs/evidence/S01E09-number18-device.md`](docs/evidence/S01E09-number18-device.md) — illuminated object/device с маркировка `18`, с неизвестна функция.
- [`docs/evidence/S01E09-jane-carmody-cleaning.md`](docs/evidence/S01E09-jane-carmody-cleaning.md) — Juliette отваря познатото cleaning видео на Jane Carmody.
- [`docs/evidence/S01E10-cleaning-helmet-tape.md`](docs/evidence/S01E10-cleaning-helmet-tape.md) — false helmet layer, tape variation и cleaner-survival mechanism.
- [`docs/evidence/S01E10-bernard-compartmentalization.md`](docs/evidence/S01E10-bernard-compartmentalization.md) — привилегирован достъп/control на Bernard и compartmentalization на Sims.
- [`docs/evidence/S01E10-multiple-silos-exterior.md`](docs/evidence/S01E10-multiple-silos-exterior.md) — barren reality, multi-Silo field и distant skyline.
- [`docs/evidence/S01E10-key18.md`](docs/evidence/S01E10-key18.md) — физически ключ с маркировка `18`.
- [`docs/evidence/S01E10-syndrome-level144-rota.md`](docs/evidence/S01E10-syndrome-level144-rota.md) — Syndrome sign, Level 144 infrastructure и Janitorial ROTA.
- [`docs/evidence/S02E01-other-silo-rebellion.md`](docs/evidence/S02E01-other-silo-rebellion.md) — rebellion във втория Silo, IT assault и масово излизане.
- [`docs/evidence/S02E01-outside-hazard-suit-breathing.md`](docs/evidence/S02E01-outside-hazard-suit-breathing.md) — outside hazard, suit seal и breathing-support model.
- [`docs/evidence/S02E01-cross-silo-surveillance-it.md`](docs/evidence/S02E01-cross-silo-surveillance-it.md) — повторено наблюдение чрез камери в огледалата и стандартизация на IT.
- [`docs/evidence/S02E01-power-flooding-survivor.md`](docs/evidence/S02E01-power-flooding-survivor.md) — residual power, flooding и surviving occupant.
- [`docs/evidence/S02E02-the-order-failed-cleaning.md`](docs/evidence/S02E02-the-order-failed-cleaning.md) — `THE ORDER`, failed-cleaning contingency и war-risk doctrine.
- [`docs/evidence/S02E02-live-cleaner-feed.md`](docs/evidence/S02E02-live-cleaner-feed.md) — live feed от външната среда, свързан с Juliette, и границата на предаването.
- [`docs/evidence/S02E02-cleaning-tape-mechanism.md`](docs/evidence/S02E02-cleaning-tape-mechanism.md) — разграничение между добра/лоша лента и модел на ограничена защита.
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
- [`docs/evidence/S02E04-vr-cleaner-technology.md`](docs/evidence/S02E04-vr-cleaner-technology.md) — immersive headset с Monteverde и връзката му с технологията на cleaner helmet.
- [`docs/evidence/S02E04-meadows-framing-sims.md`](docs/evidence/S02E04-meadows-framing-sims.md) — убийството на Meadows, framing на Mechanical и натискът на Sims.
- [`docs/evidence/S02E04-silo17-child-vault.md`](docs/evidence/S02E04-silo17-child-vault.md) — survivor-ът от Silo 17 като дете и vault continuity-refuge model.
- [`docs/evidence/S02E05-sims-judge-shadow.md`](docs/evidence/S02E05-sims-judge-shadow.md) — reassignment на Sims, Judge office и отделен shadow succession path.
- [`docs/evidence/S02E05-silo17-power-flooding-recovery.md`](docs/evidence/S02E05-silo17-power-flooding-recovery.md) — независимо IT захранване, саботаж на помпата на Level 144, наводняване и план за възстановяване.
- [`docs/evidence/S02E05-it-judicial-infrastructure-map.md`](docs/evidence/S02E05-it-judicial-infrastructure-map.md) — schematic lines, свързани с IT/Judicial, и hidden-backbone hypothesis.
- [`docs/evidence/S02E05-salvador-quinn-letter.md`](docs/evidence/S02E05-salvador-quinn-letter.md) — сканирано Quinn letter и encoded final payload.
- [`docs/evidence/S02E06-institutional-messaging.md`](docs/evidence/S02E06-institutional-messaging.md) — direct messaging, coexistence с courier и layered communication access.
- [`docs/evidence/S02E06-control-room-humint.md`](docs/evidence/S02E06-control-room-humint.md) — routed field/HUMINT reporting към control-room operational picture.
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
- [`docs/evidence/S02E09-hidden-lower-contact.md`](docs/evidence/S02E09-hidden-lower-contact.md) — Active lower contact и previous visitors Quinn/Meadows/George.
- [`docs/evidence/S02E09-silo17-vault-knowledge.md`](docs/evidence/S02E09-silo17-vault-knowledge.md) — среда за съхраняване на знание във vault-а на Silo 17.
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

Това не означава, че всички официални записи са неверни. Означава, че официалните записи се класифицират като institutional claims, когато няма независимо потвърждение.

### Допълнително правило след S01E06

**Загуба на публично знание ≠ пълна загуба на институционално знание.** Ограничената база данни за реликви показва, че избрани pre-Silo записи са запазени в привилегировани системи. Скритото наблюдение също вече е директно потвърдена инфраструктура, а не само извод от досието.

### Допълнително правило след S01E07

**Direct confession / direct observation > историческо обяснение.**

S01E07 съдържа както директно потвърдени механизми, така и исторически свидетелства. Например:
- retained-implant deception е independently corroborated чрез Allison physical evidence + Juliette’s father confession;
- потискането на паметта чрез водата и насочването срещу семейните линии на Flamekeepers остават исторически твърдения до независимо потвърждение;
- Flamekeepers не се приравняват автоматично с Rebels, докато episode evidence не establish-не връзката.

### Допълнително правило след S01E08

**Character belief може да бъде superseded от новонаблюдаван механизъм; institutional testimony само по себе си може да бъде coercive mechanism.**

- По-ранното убеждение на Juliette, че баща ѝ е издал микроскопа, вече не е необходимо, след като наблюдението чрез огледалата е известно и тя самата свързва двете.
- Твърдението Mayor/Sims „she wants to go out“ се следи отделно от това, което Juliette реално е казала; последвалият арест не прави твърдението ретроактивно вярно.

### Допълнително правило след S01E09

**Evidence, което става известно на персонаж, се следи отделно от evidence, вече известно на зрителя/проекта.**

Cleaning видеото на Jane Carmody вече беше директно визуално evidence в S01E01. S01E09 е важно, защото Juliette сама получава достъп до същото evidence; това не прави зеленото изображение изведнъж вярно и не решава дали е реално или манипулирано.

### Допълнително правило след S01E10

**Заключенията на персонажите остават отделни от директните системни разкрития.** Juliette първоначално заключава, че публичният екран е лъжата, защото шлемът ѝ показва зелено изображение; S01E10 след това директно разкрива, че самото изображение в шлема е невярно. Затова ledger-ът пази нейното твърдение като извод на персонаж, а по-късното разкритие — като evidence от по-висок клас.

### Допълнително правило след S02E01

**Повторението между Silos укрепва hypotheses за стандартизация, а не автоматични изводи за централен контрол.** Когато същата архитектура се появява във втори Silo — камери в огледалата, IT, airlock, земеделие — можем по-силно да изведем общ дизайн/doctrine, но не заключаваме автоматично, че една активна централна власт контролира всеки Silo.

**Superseded inferences остават в history.** E188 запазва първоначалната погрешна Engineering/generator-target interpretation и я маркира като superseded, след като по-късен scene evidence идентифицира IT като действителната attacked/defended location.

### Допълнително правило след S02E02

**Привилегированата doctrine, вътрешната интерпретация и директният механизъм остават отделни evidence classes.** Заглавието в `THE ORDER` е директно институционално evidence; обясненията на Bernard/Meadows за лентата са вътрешни свидетелства; точният инженерен механизъм остава неустановен, докато не бъде директно установен.

**Repeated cross-Silo secured architecture подкрепя standardization, а не identical contents.** Подобните IT vault-like compartments в два Silos strengthen-ват H38, без да приемаме, че съдържат едни и същи systems, хора или doctrine.

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

След S01E05 публичният екран има normal day/night states, systematic celestial temporal behavior и abnormal lush power-down state.

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

**Candidate → Active → Strengthened → Weakened → Refactored → Rejected → Confirmed**

`Confirmed` се използва пестеливо.

Ако нова информация опровергава само част от theory, предпочитаме **refactor**, вместо да я защитаваме на всяка цена.


### Допълнително правило след S02E05

**Формалната длъжност и скритото наследяване са отделни evidence layers.** Това, че Bernard назначава Sims за Judge, но му отказва ролята `shadow`, показва, че публичният институционален ранг не означава автоматично достъп до най-дълбокия IT succession/read-in path.

**Чертежите с инфраструктурни линии не се интерпретират сами.** Линия, стигаща до IT или Judicial, се записва като връзка/път на схемата; интерпретациите за захранване, данни, комуникации, контрол и utility остават конкуриращи се, докато диаграма или диалог не идентифицира услугата.



### Допълнително правило след S02E06

**Съществуване на технология ≠ универсален достъп до нея.** Direct messaging на институционални терминали доказва, че Silo има способност за digital комуникация, но не доказва, че обикновените жители имат равен достъп до крайни точки/акаунти.

**Комуникационните канали се моделират отделно според достъпа и контрола.** Куриера, digital messaging и радиото могат да съществуват паралелно, защото обслужват различни групи/функции. Способността на IT да прекъсва радиото е evidence за контрол върху този канал, а не автоматично доказателство, че IT чете всяко digital message или контролира всяка физическа комуникация.

**Почти реалновремевото полево докладване ≠ директно доказателство за изходния терминал.** Докладът в control room установява digital HUMINT/полеви reporting pipeline, но изходното устройство, посредникът и протоколът остават неустановени.



### Допълнително правило след S02E07

**Защитено съхраняване на знание ≠ публична историческа приемственост.** Библиотеката `Legacy` показва, че привилегировано историческо/техническо знание може да бъде умишлено запазено, докато обикновените жители губят или нямат достъп до широк исторически контекст.

**Функционална резервираност ≠ идентична архитектура на източника.** Това, че IT в Silo 18 остава захранен при blackout, доказва резервно/continuity power, но само по себе си не доказва същия външен източник, описан за Silo 17.

**Разпространявано съобщение ≠ проверено авторство или истина.** Anti-IT листовката е директно evidence, че съществува контраразказ. Нейните твърдения, автор, разпространител и официална подкрепа от Mechanical се следят отделно.

**Изведената хронология запазва приблизителността.** `352 years since construction - ~140 years since Rebellion ≈ 212 pre-Rebellion years` е силен изведен ориентир, но приблизителните входни свидетелства не се превръщат мълчаливо в точни календарни дати.



### Допълнително правило след S02E08

**Привилегированото историческо свидетелство може да отхвърли официалния разказ, без автоматично да се превръща във всезнаеща истина.** Bernard директно идентифицира публичния разказ за Quinn като неверен и дава последователен скрит механизъм, но мотивите на Quinn и причинното твърдение, че самата историческа памет е пораждала бунтове, остават проследявани като привилегировано историческо свидетелство.

**Потвърден механизъм ≠ идентично вещество.** Свидетелството за паметта и водата в S01E07 + разказът на Bernard в S02E08 силно установяват историческо потискане на паметта чрез водата, докато S02E03 доказва, че съществува текущо лекарство за забравяне. Точната идентичност на съединението между различните ери остава неустановена.

**Историческото заличаване и историческото съхраняване могат да съществуват едновременно по дизайн.** Публичните записи/книги/памет могат да бъдат потискани, докато `Legacy` и други привилегировани системи пазят избрана истина. Моделът е контролиран достъп, а не пълно унищожение.

**Association със стар документ ≠ authorship.** Ръкописното `Salvador Quinn` върху `The Pact Between the Founders` го асоциира директно с това копие, но не установява, че е автор на Pact, че е Founder или че е променял текста му.

**Декодирана фраза ≠ декодирана система.** `the game is rigged` („играта е нагласена“) е директно evidence от съобщението на Quinn, но точният референт на `the game` остава отворен.


## Текущ модел за външния свят

След S02E08 основната визуална неяснота за външната среда остава разрешена. S02E08 не променя съществено модела за външната опасност; директно променя модела за обитаване на Silo 17, като потвърждава множество живи обитатели:

1. **Lush cleaner view is false** — helmet-ът показва manipulated / overlay-like visual layer.
2. **Barren exterior is substantially real** — след отпадането на false layer Juliette вижда devastated terrain.
3. **Съществуват множество Silo инсталации**; оцелял от Silo 17 заявява точен брой на системата **50**.
4. В далечината се вижда **ruined / city-like skyline**, но identity/location не са установени.
5. Juliette директно достига и влиза във **втори Silo**.
6. Голямо mass-remains field около този Silo потвърждава real lethal опасността във външната среда при наблюдаваните условия.
7. Текущият най-подходящ клас на опасността е **подвижна въздушна/прахова опасност**, чиято локална концентрация може временно да се разсее и после да се върне; точният механизъм токсин/патоген/частици остава неустановен.
8. Suit sealing и breathing-support integrity влияят съществено върху survival.
9. Insider dialogue силно свързва оцеляването на Juliette със замяната на normal cleaning tape с по-добър seal.
10. Bernard/IT получава live exterior video, свързано с Juliette, докато тя е навън.
11. Silo 17 показва, че ако expected death на cleaner не бъде наблюдавана, може да възникне belief „outside is safe“ и mass-exit cascade.
12. Juliette изрично идентифицира repeated lush visual sequence като cleaning-behavior trigger.
13. Bernard демонстрира standalone immersive headset с preserved pre-Silo natural environment и обяснява, че работи подобно на cleaner-helmet imagery.
14. S02E08 директно потвърждава multiple living inhabitants в Silo 17 отвъд познатия досега IT-vault survivor.

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
analysis/S02E09-hidden-lower-system
analysis/S02E10-safeguard-presilo-washington
analysis/S03E01-memory-control-supervisory-system
analysis/S03E02-memory-retrieval-population-control
analysis/S03E03-safeguard-isolation-deception
analysis/S03E04-covert-network-abyss-bernard
analysis/S03E05-voice-safeguard-memory-control
analysis/S03E06-silo1-power-voice-memory
analysis/S03E07-exterior-enforcement-georgia
analysis/S03E08-nano-topology-safeguard
analysis/S03E09-voice-pact-opening
hypothesis/<name>
model/<name>
methodology/<change>
```

Git history е част от разследването: трябва да можем да видим кога е възникнала една theory, кой evidence я е укрепил, кой я е отслабил и кога е била refactor-ната или отхвърлена.

---

**Текуща knowledge boundary:** `S03E09`
