# S02E01 — Опасност във външната среда, уплътнение на костюма и дихателна поддръжка

**Knowledge boundary:** `S02E01`

## Direct observations

- външната зона около втория Силоз е покрита с голямо поле от човешки останки;
- тези останки съответстват на историческа последователност на масово излизане;
- Juliette оцелява навън, докато е защитена от костюма си;
- вътре във втория Силоз Juliette развива остър дихателен дистрес, докато остава запечатана в средата на костюма и шлема;
- след счупване/отваряне на шлема тя може да диша вътрешната атмосфера на втория Силоз.

## Model update

Най-силният текущ модел е:

```text
real outside hazard
        +
целостта на suit sealing / breathing support има значение
```

Possible poor-seal pathways:

1. външен опасен материал влиза през повредено уплътнение;
2. breathing gas изтича по-бързо и supply се изчерпва;
3. и двата механизма работят едновременно.

Точният механизъм все още не се приема за установен.

## H14

Смъртността при почистване зависи съществено от уплътнението на костюма **и целостта на дихателната поддръжка**.

**Confidence:** VH  
**Status:** Strongly Strengthened / Refactored

## H34

Стандартната лента за почистване може да е умишлено или системно по-лоша.

S02E01 refines possible effects:
- contaminant ingress;
- breathing-gas loss;
- both.

**Confidence:** H  
**Status:** Active / Refactored

## H36

Смъртоносността на външната среда се причинява основно от **опасност, пренасяна по въздуха / в атмосферата**.

**Confidence:** H  
**Status:** Active / Strengthened

Current candidates include:
- toxic gas / chemical contaminant;
- aerosol / particulate;
- biological/pathogen exposure;
- other atmosphere-borne agent.

Чистата външна радиация като единствен непосредствен убиец е отслабена като обяснение, защото evidence-ът за уплътнението/дишането съответства по-добре на модел за проникване/излагане. Радиоактивни частици във въздуха остават физически възможни, но не са подкрепени от доказателствата.

## Граници

Do not assert:
- oxygen tank;
- rebreather;
- positive-pressure suit;
- exact toxin/pathogen;
- точният механизъм, определящ времето до смъртта.

## Визуални доказателства

- [Масови останки около втория Силоз](../../assets/S02E01/screenshots/other-silo-hatch-mass-remains-wide.jpeg)
- [Дихателният проблем на Juliette в костюма](../../assets/S02E01/screenshots/juliette-suit-air-failure.jpeg)
