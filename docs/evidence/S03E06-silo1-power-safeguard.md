# S03E06 — Silo 1 захранване и safeguard routing

**Граница на знанието:** `S03E06`

## External electrical видеопоток към IT

Bernard обяснява, че линия, която идва отвън и стига до IT, е electrical и захранва IT.

Следващото ключово твърдение е, че тази line идва от **Silo 1**.

Това дава конкретен upstream механизъм за previously observed independent IT захранване. Най-силният current reconstruction е:

```text
Silo 1
  │
  └── external electrical feed
             │
             ▼
            IT
```

Този модел не изключва локален backup generation; просто вече не е нужно локален backup да бъде единственото обяснение.

## Relation към radio monitoring

S03E05 директно установява, че Silo 1 следи active radio frequencies на другите Silos.

S03E06 добавя втори privileged инфраструктура role:
- централен radio visibility;
- external IT electrical supply.

Това materially strengthens модел-а, че Silo 1 е централен инфраструктура node, но **не доказва, че Silo 1 = „Гласът“**.

## Safeguard path към Judicial

В същото architectural reasoning safeguard line-ът се отделя като маршрут към Judicial.

Работният модел е:

```text
external infrastructure
   ├── electrical feed → IT
   │        ↑
   │     Silo 1
   │
   └── safeguard path → Judicial
```

Epistemic boundary:
- Silo 1 origin е пряк-stated за electrical видеопоток-а;
- source-ът на safeguard path-а остава неизяснен;
- точен физически nature на safeguard line-а остава неизяснен;
- локален endpoint при Judicial не е автоматично equal на activation controller.

## исторически reinterpretation

По-ранното доказателство за IT захранване непрекъснатост при локален outages може да се преинтерпретира чрез external Silo 1 видеопоток.

Това е refinement, не overwrite: старото наблюдение остава валидно; новото доказателство предлага конкретен механизъм.
