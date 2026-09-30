# S01E03 — Public display power-down flash

**Knowledge boundary:** `S01E03 only`

Тази бележка изолира един от най-важните exterior-system datapoints до момента: при planned power-down public display за кратък момент показва lush exterior imagery.

![Public display lush flash](../../assets/S01E03/screenshots/public-display-lush-flash-during-powerdown.jpeg)

## Direct observation

Нормалното public display състояние е barren/gray exterior.

При изключването на display-а картината за момент преминава към lush/green exterior representation.

## Какво доказва

- public-display pipeline има достъп до повече от едно exterior visual state;
- lush imagery не е ограничено само до cleaner helmet-а;
- public display не може да се моделира като прост transparent monitor на един unprocessed source;
- между physical source и displayed image вероятно има processing/state layer.

## Какво не доказва

- кой visual state е real;
- дали lush state е live feed;
- дали barren state е live feed;
- дали lush state е overlay, cached frame, fallback, test image или друг artifact;
- дали cleaner helmet и public display използват един и същ exact source.

## Relation към предишния evidence

S01E01:

- public display: barren;
- Allison helmet: lush;
- Jane Carmody recording: lush.

S01E02:

- Holston helmet: lush;
- едновременно public display: barren.

S01E03:

- при shutdown **самият public display** за момент показва lush image.

Така exterior contradiction вече не е само conflict между два устройства. Имаме evidence, че **един и същ public presentation endpoint може да покаже radically different exterior representations**.

## Hypothesis impact

### H1 — deliberate/manipulated exterior visual pipeline

`VH → VH (Strengthened)`

Evidence quality се увеличава значително.

### H3 — barren substantially real / lush overlay

Остава `H`.

Power-down behavior е compatible с overlay/state-switch model, но не удостоверява barren reality.

### Model C — neither feed fully authentic

Остава силно viable.

## Falsification targets

Следващите епизоди трябва да се следят за:

- system diagnostics / display architecture;
- source labels или routing;
- други power-cycle artifacts;
- reaction на residents/authorities към lush flash;
- whether lush frame matches cleaner imagery pixel-for-pixel или само тематично;
- independent exterior observation извън controlled displays.
