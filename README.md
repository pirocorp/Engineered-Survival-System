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
- Sims оперативно ръководи наблюдението. Съдия Meadows и медицинският център също са наблюдавани.
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
## Карта на хранилището

- [`CURRENT_STATE.md`](CURRENT_STATE.md) — текущ синтез след последния изгледан епизод.
- [`docs/episodes/S01E01.md`](docs/episodes/S01E01.md) — запис за епизод S01E01.
- [`docs/episodes/S01E02.md`](docs/episodes/S01E02.md) — запис за епизод S01E02.
- [`docs/episodes/S01E03.md`](docs/episodes/S01E03.md) — запис за епизод S01E03.
- [`docs/episodes/S01E04.md`](docs/episodes/S01E04.md) — запис за епизод S01E04.
- [`docs/episodes/S01E05.md`](docs/episodes/S01E05.md) — запис за епизод S01E05.
- [`docs/episodes/S01E06.md`](docs/episodes/S01E06.md) — запис за епизод S01E06.
- [`docs/episodes/S01E07.md`](docs/episodes/S01E07.md) — запис за епизод S01E07.
- [`docs/episodes/S01E08.md`](docs/episodes/S01E08.md) — запис за епизод S01E08.
- [`docs/episodes/S01E09.md`](docs/episodes/S01E09.md) — запис за епизод S01E09.
- [`docs/episodes/S01E10.md`](docs/episodes/S01E10.md) — запис за епизод S01E10.
- [`docs/episodes/S02E01.md`](docs/episodes/S02E01.md) — запис за епизод S02E01.
- [`docs/episodes/S02E02.md`](docs/episodes/S02E02.md) — запис за епизод S02E02.
- [`docs/episodes/S02E03.md`](docs/episodes/S02E03.md) — запис за епизод S02E03.
- [`docs/episodes/S02E04.md`](docs/episodes/S02E04.md) — запис за епизод S02E04.
- [`docs/episodes/S02E05.md`](docs/episodes/S02E05.md) — запис за епизод S02E05.
- [`docs/episodes/S02E06.md`](docs/episodes/S02E06.md) — запис за епизод S02E06.
- [`docs/episodes/S02E07.md`](docs/episodes/S02E07.md) — запис за епизод S02E07.
- [`docs/episodes/S02E08.md`](docs/episodes/S02E08.md) — запис за епизод S02E08.
- [`docs/episodes/S02E09.md`](docs/episodes/S02E09.md) — запис за епизод S02E09.
- [`docs/episodes/S02E10.md`](docs/episodes/S02E10.md) — запис за епизод S02E10.
- [`docs/episodes/S03E01.md`](docs/episodes/S03E01.md) — запис за епизод S03E01.
- [`docs/episodes/S03E02.md`](docs/episodes/S03E02.md) — запис за епизод S03E02.
- [`docs/episodes/S03E03.md`](docs/episodes/S03E03.md) — запис за епизод S03E03.
- [`docs/episodes/S03E04.md`](docs/episodes/S03E04.md) — запис за епизод S03E04.
- [`docs/episodes/S03E05.md`](docs/episodes/S03E05.md) — запис за епизод S03E05.
- [`docs/episodes/S03E06.md`](docs/episodes/S03E06.md) — запис за епизод S03E06.
- [`docs/episodes/S03E10.md`](docs/episodes/S03E10.md) — запис за епизод S03E10.
- [`docs/evidence/S03E10-silo1-stasis-memory.md`](docs/evidence/S03E10-silo1-stasis-memory.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E10-safeguard-drone-directive.md`](docs/evidence/S03E10-safeguard-drone-directive.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E10-voice-control-room-victor-camille.md`](docs/evidence/S03E10-voice-control-room-victor-camille.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E10-second-vault-daniel-juliette.md`](docs/evidence/S03E10-second-vault-daniel-juliette.md) — тематичен доказателствен запис.
- [`assets/S03E10/MANIFEST.md`](assets/S03E10/MANIFEST.md) — манифест на визуалните доказателства.
- [`docs/audits/S03-consistency-audit.md`](docs/audits/S03-consistency-audit.md) — одит на методологията и консистентността.
- [`docs/episodes/S03E09.md`](docs/episodes/S03E09.md) — запис за епизод S03E09.
- [`docs/evidence/S03E09-voice-bernard-cleaning.md`](docs/evidence/S03E09-voice-bernard-cleaning.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E09-exterior-mines-pact.md`](docs/evidence/S03E09-exterior-mines-pact.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E09-opening-topology-intake.md`](docs/evidence/S03E09-opening-topology-intake.md) — тематичен доказателствен запис.
- [`assets/S03E09/MANIFEST.md`](assets/S03E09/MANIFEST.md) — манифест на визуалните доказателства.
- [`docs/episodes/S03E08.md`](docs/episodes/S03E08.md) — запис за епизод S03E08.
- [`docs/evidence/S03E08-exterior-bernard.md`](docs/evidence/S03E08-exterior-bernard.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E08-presilo-nanotechnology-iran.md`](docs/evidence/S03E08-presilo-nanotechnology-iran.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E08-silo-topology-safeguard.md`](docs/evidence/S03E08-silo-topology-safeguard.md) — тематичен доказателствен запис.
- [`assets/S03E08/MANIFEST.md`](assets/S03E08/MANIFEST.md) — манифест на визуалните доказателства.
- [`docs/episodes/S03E07.md`](docs/episodes/S03E07.md) — запис за епизод S03E07.
- [`docs/evidence/S03E07-exterior-voice-safeguard.md`](docs/evidence/S03E07-exterior-voice-safeguard.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E07-presilo-georgia-memory.md`](docs/evidence/S03E07-presilo-georgia-memory.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E07-console-feed-control.md`](docs/evidence/S03E07-console-feed-control.md) — тематичен доказателствен запис.
- [`assets/S03E07/MANIFEST.md`](assets/S03E07/MANIFEST.md) — манифест на визуалните доказателства.
- [`docs/evidence/S03E06-silo1-power-safeguard.md`](docs/evidence/S03E06-silo1-power-safeguard.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E06-juliette-voice-memory.md`](docs/evidence/S03E06-juliette-voice-memory.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E06-vitamin-d-water.md`](docs/evidence/S03E06-vitamin-d-water.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E06-presilo-iran-takeover.md`](docs/evidence/S03E06-presilo-iran-takeover.md) — тематичен доказателствен запис.
- [`assets/S03E06/MANIFEST.md`](assets/S03E06/MANIFEST.md) — манифест на визуалните доказателства.
- [`docs/evidence/S03E05-sims-voice-safeguard.md`](docs/evidence/S03E05-sims-voice-safeguard.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E05-bernard-fake-death-robert-network.md`](docs/evidence/S03E05-bernard-fake-death-robert-network.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E05-memory-relic-radio.md`](docs/evidence/S03E05-memory-relic-radio.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E05-presilo-ai-iran-vehicle.md`](docs/evidence/S03E05-presilo-ai-iran-vehicle.md) — тематичен доказателствен запис.
- [`assets/S03E05/MANIFEST.md`](assets/S03E05/MANIFEST.md) — манифест на визуалните доказателства.
- [`docs/evidence/S03E04-memory-escape-network.md`](docs/evidence/S03E04-memory-escape-network.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E04-presilo-cooptation-pentagon.md`](docs/evidence/S03E04-presilo-cooptation-pentagon.md) — тематичен доказателствен запис.
- [`docs/evidence/S03E04-deep-route-bernard.md`](docs/evidence/S03E04-deep-route-bernard.md) — тематичен доказателствен запис.
- [`assets/S03E04/MANIFEST.md`](assets/S03E04/MANIFEST.md) — манифест на визуалните доказателства.
- [`docs/evidence-ledger.md`](docs/evidence-ledger.md) — централен регистър на доказателствата.
- [`docs/evidence/S01E01-exterior-visual-contradiction.md`](docs/evidence/S01E01-exterior-visual-contradiction.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E02-holston-visual-split.md`](docs/evidence/S01E02-holston-visual-split.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E02-sub-silo-construction-layer.md`](docs/evidence/S01E02-sub-silo-construction-layer.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E03-public-display-powerdown-flash.md`](docs/evidence/S01E03-public-display-powerdown-flash.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E04-sheriff-succession-and-control.md`](docs/evidence/S01E04-sheriff-succession-and-control.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E05-surveillance-trumbull-coverup.md`](docs/evidence/S01E05-surveillance-trumbull-coverup.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E05-celestial-observation.md`](docs/evidence/S01E05-celestial-observation.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E05-pact-capability-restrictions.md`](docs/evidence/S01E05-pact-capability-restrictions.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E06-centralized-surveillance.md`](docs/evidence/S01E06-centralized-surveillance.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E06-relic-database-pre-silo.md`](docs/evidence/S01E06-relic-database-pre-silo.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E06-georgia-relic.md`](docs/evidence/S01E06-georgia-relic.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E07-surveillance-command-and-mirrors.md`](docs/evidence/S01E07-surveillance-command-and-mirrors.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E07-flamekeepers-memory-erasure.md`](docs/evidence/S01E07-flamekeepers-memory-erasure.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E07-reproductive-control.md`](docs/evidence/S01E07-reproductive-control.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E07-flamekeeper-family-network.md`](docs/evidence/S01E07-flamekeeper-family-network.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E08-illicit-microscopy-and-mirror-surveillance.md`](docs/evidence/S01E08-illicit-microscopy-and-mirror-surveillance.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E08-fabricated-cleaning-trigger.md`](docs/evidence/S01E08-fabricated-cleaning-trigger.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E08-bernard-judge-power.md`](docs/evidence/S01E08-bernard-judge-power.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E09-level23-escape.md`](docs/evidence/S01E09-level23-escape.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E09-number18-device.md`](docs/evidence/S01E09-number18-device.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E09-jane-carmody-cleaning.md`](docs/evidence/S01E09-jane-carmody-cleaning.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E10-cleaning-helmet-tape.md`](docs/evidence/S01E10-cleaning-helmet-tape.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E10-bernard-compartmentalization.md`](docs/evidence/S01E10-bernard-compartmentalization.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E10-multiple-silos-exterior.md`](docs/evidence/S01E10-multiple-silos-exterior.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E10-key18.md`](docs/evidence/S01E10-key18.md) — тематичен доказателствен запис.
- [`docs/evidence/S01E10-syndrome-level144-rota.md`](docs/evidence/S01E10-syndrome-level144-rota.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E01-other-silo-rebellion.md`](docs/evidence/S02E01-other-silo-rebellion.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E01-outside-hazard-suit-breathing.md`](docs/evidence/S02E01-outside-hazard-suit-breathing.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E01-cross-silo-surveillance-it.md`](docs/evidence/S02E01-cross-silo-surveillance-it.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E01-power-flooding-survivor.md`](docs/evidence/S02E01-power-flooding-survivor.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E02-the-order-failed-cleaning.md`](docs/evidence/S02E02-the-order-failed-cleaning.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E02-live-cleaner-feed.md`](docs/evidence/S02E02-live-cleaner-feed.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E02-cleaning-tape-mechanism.md`](docs/evidence/S02E02-cleaning-tape-mechanism.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E02-it-vault-governance.md`](docs/evidence/S02E02-it-vault-governance.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E03-silo17-failed-cleaning-rebellion.md`](docs/evidence/S02E03-silo17-failed-cleaning-rebellion.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E03-outside-hazard-cleaner-death.md`](docs/evidence/S02E03-outside-hazard-cleaner-death.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E03-memory-suppression.md`](docs/evidence/S02E03-memory-suppression.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E03-key18-server-room-vault.md`](docs/evidence/S02E03-key18-server-room-vault.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E03-silo-orange-chronology.md`](docs/evidence/S02E03-silo-orange-chronology.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E03-cleaner-perception-pattern.md`](docs/evidence/S02E03-cleaner-perception-pattern.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E04-mechanical-scapegoating.md`](docs/evidence/S02E04-mechanical-scapegoating.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E04-mines-penal-labor.md`](docs/evidence/S02E04-mines-penal-labor.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E04-salvador-quinn-meadows.md`](docs/evidence/S02E04-salvador-quinn-meadows.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E04-vr-cleaner-technology.md`](docs/evidence/S02E04-vr-cleaner-technology.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E04-meadows-framing-sims.md`](docs/evidence/S02E04-meadows-framing-sims.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E04-silo17-child-vault.md`](docs/evidence/S02E04-silo17-child-vault.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E05-sims-judge-shadow.md`](docs/evidence/S02E05-sims-judge-shadow.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E05-silo17-power-flooding-recovery.md`](docs/evidence/S02E05-silo17-power-flooding-recovery.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E05-it-judicial-infrastructure-map.md`](docs/evidence/S02E05-it-judicial-infrastructure-map.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E05-salvador-quinn-letter.md`](docs/evidence/S02E05-salvador-quinn-letter.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E06-institutional-messaging.md`](docs/evidence/S02E06-institutional-messaging.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E06-control-room-humint.md`](docs/evidence/S02E06-control-room-humint.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E06-radio-communications-control.md`](docs/evidence/S02E06-radio-communications-control.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E07-legacy-vault.md`](docs/evidence/S02E07-legacy-vault.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E07-352-year-chronology.md`](docs/evidence/S02E07-352-year-chronology.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E07-anti-it-counter-narrative.md`](docs/evidence/S02E07-anti-it-counter-narrative.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E07-silo18-continuity-power.md`](docs/evidence/S02E07-silo18-continuity-power.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E08-quinn-historical-reset.md`](docs/evidence/S02E08-quinn-historical-reset.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E08-memory-suppression-water.md`](docs/evidence/S02E08-memory-suppression-water.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E08-meadows-quinn-pact.md`](docs/evidence/S02E08-meadows-quinn-pact.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E08-quinn-decoded-message.md`](docs/evidence/S02E08-quinn-decoded-message.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E08-sims-ahundsen-message.md`](docs/evidence/S02E08-sims-ahundsen-message.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E08-silo17-multiple-survivors.md`](docs/evidence/S02E08-silo17-multiple-survivors.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E09-quinn-safeguard-tunnel.md`](docs/evidence/S02E09-quinn-safeguard-tunnel.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E09-hidden-lower-contact.md`](docs/evidence/S02E09-hidden-lower-contact.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E09-silo17-vault-knowledge.md`](docs/evidence/S02E09-silo17-vault-knowledge.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E09-silo17-survivor-group.md`](docs/evidence/S02E09-silo17-survivor-group.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E09-coercive-message.md`](docs/evidence/S02E09-coercive-message.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E10-safeguard-poison-system.md`](docs/evidence/S02E10-safeguard-poison-system.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E10-silo18-rebellion-return-airlock.md`](docs/evidence/S02E10-silo18-rebellion-return-airlock.md) — тематичен доказателствен запис.
- [`docs/evidence/S02E10-presilo-washington-georgia-iran-pez.md`](docs/evidence/S02E10-presilo-washington-georgia-iran-pez.md) — тематичен доказателствен запис.
- [`docs/open-questions.md`](docs/open-questions.md) — активни отворени въпроси и критерии за проверка.
- [`assets/S01E01/screenshots/`](assets/S01E01/screenshots/) — избрани визуални доказателства.
- [`assets/S01E02/screenshots/`](assets/S01E02/screenshots/) — избрани визуални доказателства.
- [`assets/S01E03/screenshots/`](assets/S01E03/screenshots/) — избрани визуални доказателства.
- [`assets/S01E04/screenshots/`](assets/S01E04/screenshots/) — избрани визуални доказателства.
- [`assets/S01E05/screenshots/`](assets/S01E05/screenshots/) — избрани визуални доказателства.
- [`assets/S01E06/screenshots/`](assets/S01E06/screenshots/) — избрани визуални доказателства.
- [`assets/S01E07/screenshots/`](assets/S01E07/screenshots/) — избрани визуални доказателства.
- [`assets/S01E07/MANIFEST.md`](assets/S01E07/MANIFEST.md) — манифест на визуалните доказателства.
- [`assets/S01E08/screenshots/`](assets/S01E08/screenshots/) — избрани визуални доказателства.
- [`assets/S01E08/MANIFEST.md`](assets/S01E08/MANIFEST.md) — манифест на визуалните доказателства.
- [`assets/S01E09/screenshots/`](assets/S01E09/screenshots/) — избрани визуални доказателства.
- [`assets/S01E09/MANIFEST.md`](assets/S01E09/MANIFEST.md) — манифест на визуалните доказателства.
- [`assets/S01E10/screenshots/`](assets/S01E10/screenshots/) — избрани визуални доказателства.
- [`assets/S01E10/MANIFEST.md`](assets/S01E10/MANIFEST.md) — манифест на визуалните доказателства.
- [`assets/S02E01/screenshots/`](assets/S02E01/screenshots/) — избрани визуални доказателства.
- [`assets/S02E01/MANIFEST.md`](assets/S02E01/MANIFEST.md) — манифест на визуалните доказателства.
- [`assets/S02E02/screenshots/`](assets/S02E02/screenshots/) — избрани визуални доказателства.
- [`assets/S02E02/MANIFEST.md`](assets/S02E02/MANIFEST.md) — манифест на визуалните доказателства.
- [`assets/S02E03/screenshots/`](assets/S02E03/screenshots/) — избрани визуални доказателства.
- [`assets/S02E03/MANIFEST.md`](assets/S02E03/MANIFEST.md) — манифест на визуалните доказателства.
- [`assets/S02E04/screenshots/`](assets/S02E04/screenshots/) — избрани визуални доказателства.
- [`assets/S02E04/MANIFEST.md`](assets/S02E04/MANIFEST.md) — манифест на визуалните доказателства.
- [`assets/S02E05/screenshots/`](assets/S02E05/screenshots/) — избрани визуални доказателства.
- [`assets/S02E05/MANIFEST.md`](assets/S02E05/MANIFEST.md) — манифест на визуалните доказателства.
- [`assets/S02E06/screenshots/`](assets/S02E06/screenshots/) — избрани визуални доказателства.
- [`assets/S02E06/MANIFEST.md`](assets/S02E06/MANIFEST.md) — манифест на визуалните доказателства.
- [`assets/S02E07/screenshots/`](assets/S02E07/screenshots/) — избрани визуални доказателства.
- [`assets/S02E07/MANIFEST.md`](assets/S02E07/MANIFEST.md) — манифест на визуалните доказателства.
- [`assets/S02E08/screenshots/`](assets/S02E08/screenshots/) — избрани визуални доказателства.
- [`assets/S02E08/MANIFEST.md`](assets/S02E08/MANIFEST.md) — манифест на визуалните доказателства.
- [`assets/S02E09/screenshots/`](assets/S02E09/screenshots/) — избрани визуални доказателства.
- [`assets/S02E09/MANIFEST.md`](assets/S02E09/MANIFEST.md) — манифест на визуалните доказателства.
- [`assets/S02E10/screenshots/`](assets/S02E10/screenshots/) — избрани визуални доказателства.
- [`assets/S02E10/MANIFEST.md`](assets/S02E10/MANIFEST.md) — манифест на визуалните доказателства.



## Основна директива

Проектът следва едно основно правило:

> **Не приемаме обяснение само защото звучи правдоподобно. Всяко твърдение трябва да бъде отделено като пряко наблюдение, свидетелство на персонаж, институционално твърдение, извод или спекулация.**

Нова информация може:
- да потвърди съществуваща хипотеза;
- да я отслаби;
- да я преформулира;
- да я отхвърли;
- да разреши част от нея, без да разреши останалото.

Историческите записи не се пренаписват мълчаливо. Когато по-късен епизод коригира по-ранен модел, старото състояние се запазва като историческа граница на знанието, а промяната се записва изрично.

### Допълнителни правила, извлечени от развитието на сериала

- **Официален запис ≠ независимо установена истина.** След доказаните манипулации около Trumbull институционалната версия се третира като твърдение, докато няма независима опора.
- **Загуба на публично знание ≠ загуба на институционално знание.** Базата данни за реликви, Legacy и защитените архиви показват отделен привилегирован слой на знание.
- **Пряко признание/наблюдение има по-висока тежест от историческо обяснение.**
- **Убеждението на персонаж може да бъде заменено от по-силен наблюдаван механизъм.**
- **Когато доказателство стане известно на персонаж, това се следи отделно от факта, че зрителят вече го знае.**
- **Изводът на персонаж не се слива с директното системно разкритие.**
- **Повторението между силози подкрепя стандартизация, но не доказва автоматично централен контрол или идентично съдържание.**
- **Привилегирована доктрина, вътрешно свидетелство и директен технически механизъм са различни класове доказателства.**
- **Историческо свидетелство може да потвърди модел, без да се превръща в обективна телеметрия.**
- **Противоречията в хронологията се запазват, вместо да се нормализират насила.**
- **Кризисният разказ може сам по себе си да е проектиран управленски механизъм.**
- **Формалната длъжност и скритото наследяване са отделни слоеве на власт.**
- **Съществуване на технология ≠ универсален достъп до нея.**
- **Комуникационните канали се моделират отделно според достъпа, наблюдаемостта и контрола.**
- **Функционална резервираност ≠ идентична архитектура на източника.**
- **Разпространявано съобщение ≠ проверено авторство или истина.**
- **Асоциация със стар документ ≠ авторство.**
- **Декодирана фраза ≠ декодирана цяла система.**

## Дисциплина спрямо спойлерите

### Допустимо

- информация от епизоди до текущата граница на знанието;
- повторно анализиране на вече видени сцени и екранни снимки;
- сравняване на наблюдения от предишни епизоди;
- собствени логически изводи и конкуриращи се хипотези.

### Недопустимо

- информация от книги отвъд текущия епизод;
- уикита и интервюта с бъдещи разкрития;
- синопсиси на неизгледани епизоди;
- изтичания;
- фенски теории, които използват бъдещо знание;
- ретроспективно знание, което изкуствено прави стара хипотеза да изглежда по-силна, отколкото е била при формулирането ѝ.

Спекулативните връзки се маркират изрично. Например връзката `The Syndrome ↔ забрана за увеличение` остава спекулация с много ниска увереност, докато няма пряка опора.

## Слоеве на анализа

### Физическа система

Архитектура, инфраструктура, ресурси, енергия, въздух, вода, производство, поддръжка, технологични ограничения и физически граници.

### Система на управление

Институции, закони, забрани, йерархия, правоприлагане, наказания, разследвания и разликата между формална и реална власт.

### Информационна система

Достъп до информация, наблюдение, досиета, забранено знание, архиви, историческа памет, комуникации, образование и манипулиране на информация.

### Система за контрол на възможностите

Какво жителите физически могат да правят и наблюдават: вертикално придвижване, радио, увеличение, достъп до ограничени пространства и инструменти за независимо откриване.

### Социална система

Население, репродукция, професии, структура по нива, социална мобилност, доверие, страх, норми и отношения между нивата.

### Материална и ресурсна система

Собственост, разпределение, рециклиране, преразпределение, недостиг и затворен цикъл на използване на дълготрайни ресурси.

### Система за оцеляване

Разделяме правилата, които може реално да са необходими за оцеляване, от правилата, които могат да служат предимно за институционален контрол.

### Модел на външния свят

Следим отделно:
- физическата опасност навън;
- манипулираното изображение в шлема;
- публичния екран;
- процедурата по почистване;
- ролята на костюма и лентата;
- Safeguard и външното налагане чрез Silo 1.

## Класове доказателства

- **Пряко наблюдение** — сериалът директно показва събитието или обекта.
- **Повторено наблюдение** — поведението или моделът се появява независимо повече от веднъж.
- **Свидетелство на персонаж** — доказва какво твърди или вярва даден герой, но не непременно че твърдението е вярно.
- **Институционално твърдение** — официално правило, исторически разказ или заключение; остава твърдение до независимо потвърждение.
- **Визуално доказателство** — детайл в кадър, файл, чертеж, интерфейс или архивен запис.
- **Извод** — логическо заключение от наличните доказателства.
- **Спекулация** — възможно обяснение без достатъчна опора.

## Увереност

| Ниво | Значение |
|---|---|
| **VH** | Много силно подкрепено от множество независими наблюдения или пряко потвърждение |
| **H** | Силно подкрепено |
| **M** | Правдоподобно, но с важни алтернативи или липсваща пряка проверка |
| **L** | Възможно, но слабо или косвено подкрепено |
| **VL** | Почти чиста спекулация |

Увереността не е математическа вероятност и не замества доказателствата.

## Жизнен цикъл на хипотезите

Една хипотеза може да бъде:
- **кандидат**;
- **активна**;
- **подсилена**;
- **преформулирана**;
- **частично разрешена**;
- **потвърдена**;
- **отхвърлена**.

Когато нова информация опровергава само част от хипотезата, предпочитаме преформулиране пред изкуствено защитаване на стария вариант.

## Текущ модел за външния свят

След S03E10:

1. Зелената гледка при почистване е невярно/манипулирано визуално представяне.
2. Безплодният външен пейзаж е в значителна степен реален.
3. Реална външна опасност съществува, но точният агент и пространствено-времевият му профил остават неизяснени.
4. Стандартната смърт при почистване не се обяснява само с един прост механизъм; отрова, уплътнение на костюма, поддържане на дишането и реалната външна опасност трябва да се разглеждат отделно.
5. Silo 17 показва, че външната опасност не се държи като еднаква моментална смърт навсякъде и винаги.
6. Silo 1 разполага със собствен външен механизъм за наблюдение и смъртоносно налагане чрез дронове.
7. Следователно „навън е безопасно“ е също толкова недоказано, колкото и моделът „самият въздух убива всеки веднага“.

## Текущ архитектурен модел

```text
                         Silo 1
             централен надзор / непрекъснатост
           ┌──────────────┼──────────────┐
           │              │              │
     стаза/ръководство   „Гласът“      дронове
           │              │              │
           └──────────────┼──────────────┘
                          │
                   мрежа от 50 силоза
                          │
         ┌────────────────┴────────────────┐
         │                                 │
      Silo 18                           Silo 17
         │                                 │
   IT / Judicial                       срив/оцелели
   Legacy / трезор                     трезор/архив
   Second Vault                        прекъснат Safeguard
   блокиран Safeguard                  междусилозен контакт
```

Това е работен модел, а не окончателна схема. Всеки елемент трябва да остане свързан с конкретни доказателства.

## Работен процес след всеки епизод

1. Записваме новите наблюдения.
2. Отделяме фактите от твърденията на персонажи и институции.
3. Добавяме визуалните доказателства.
4. Проверяваме повтарящи се модели.
5. Актуализираме правилата и активните хипотези.
6. Променяме увереността само при конкретна причина.
7. Записваме противоречията.
8. Добавяме отворените въпроси.
9. Определяме какво би опровергало важните хипотези.
10. Правим PR, който запазва точното състояние на знанието след епизода.

## Git / PR философия

Промените след отделните епизоди минават през отделни клонове и PR-и.

Целта е Git историята да бъде част от разследването: да може да се види кога е възникнала една хипотеза, кои доказателства са я укрепили или отслабили и кога е била преформулирана или отхвърлена.

Не се пренаписват мълчаливо вече приети исторически състояния. Корекция се прави само когато старият запис е бил методологично или фактологично грешен за собствената си граница на знанието.

**Текуща граница на знанието:** `S03E10`
