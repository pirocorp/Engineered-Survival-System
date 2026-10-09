# Repository Одит за консистентност — Progress Notes

Branch: `audit/repo-consistency-2026-10-06`

## Scope
- Review every repository file.
- За двоичните изображения валидирай имената на файловете спрямо всички потенциални текстови препратки; поправяй счупени/несъответстващи препратки, а не съдържанието на изображенията.
- За всеки текстов файл прегледай вътрешната и междфайловата консистентност.
- Коригирай само проблеми, които могат да бъдат обосновани от доказателствата в хранилището / установеното състояние на епизодите.
- Отвори PR обратно към `main` с кратко резюме на одита.

## инвентар
- Общо одитирани файлове от началното дърво: **439**
- текстови файлове: **175**
- изображения: **264**
- Markdown файлове: **172**
- Other text: CODEOWNERS, LICENSE, one TXT visual manifest

## Завършени проверки
- [x] Инвентар на хранилището и класификация на файловете
- [x] Разрешаване на Markdown/локални препратки към ресурси и откриване на счупени пътища
- [x] Валидиране на имената на изображенията, използвани от манифести/епизоди/текстове за доказателства, спрямо реалните ресурси в хранилището
- [x] Преглед на епизодните файлове (S01–S03) за вътрешна/междфайлова консистентност
- [x] Преглед на файловете с доказателства и регистъра за междфайлови противоречия
- [x] Преглед на README / CURRENT_STATE / отворените въпроси спрямо каноничните доказателства
- [x] Check доказателство-ledger ID uniqueness
- [x] Apply потвърден консистентност fixes
- [x] Final branch recheck
- [ ] Отваряне на PR

## Structural/препратка result
- Няма действително невалидни local Markdown/image link was found.
- No canonical image filename referenced by the textual corpus was missing from the repository.
- `assets/S03E08/visual-manifest.txt` contains original `IMG_*.jpeg` source names that do not exist as repository blobs, but this is intentional: the file explicitly maps those source names to canonical repository filenames.
- регистърът на доказателствата съдържа **1149 канонични реда / 1149 уникални идентификатора на доказателства**. Не са открити дублирани идентификатори. Пропуските в S03E10 namespace от гледането на живо са умишлено запазени оттеглени/предварителни ID.

## потвърден консистентност корекция
The S03E08 Iran/nanotechnology nuclear-strike line was stale in the текущ синтез:
- няколко файла описваха подземното ядрено устройство само като планиран удар;
- `docs/open-questions.md` still asked whether the device had detonated.

Canonical корекция applied:
- the small nuclear device **was detonated beneath the target facility**;
- it was placed/delivered through the approximately **120 km underground tunnel**;
- точната степен на окончателното разрушаване на съоръжението остава отворен въпрос;
- the journalist's claim that the aircraft team was intentionally used as an experiment remains an accusation/hypothesis, not independently established fact.

Updated consistently in:
- `README.md`
- `CURRENT_STATE.md`
- `docs/episodes/S03E08.md`
- `docs/evidence/S03E08-presilo-nanotechnology-iran.md`
- `docs/evidence-ledger.md`
- `docs/open-questions.md`

Two adjacent дефектни езикови конструкции in the same S03E08 paragraph were also corrected (`нанооръжиеs`, `самолета-ът`).

## одит principle preserved
Историческите епизодни файлове с изрични граници на знанието остават исторически моментни снимки. По-късни разкрития не се вмъкват ретроспективно в по-ранни ограничени файлове, освен ако самият по-ранен запис съдържа методологична/съдържателна грешка.

## Starting point
одит started from `main@0c636dc3eac1f45bd509c24b108f9789ad9fe821`.
