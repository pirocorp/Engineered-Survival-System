# S03E06 — Silo 1 power и safeguard routing

**Knowledge boundary:** `S03E06`

## External electrical feed към IT

Bernard обяснява, че линия, която идва отвън и стига до IT, е electrical и захранва IT.

Следващото ключово твърдение е, че тази line идва от **Silo 1**.

Това дава конкретен upstream mechanism за previously observed independent IT power. Най-силният current reconstruction е:

```text
Silo 1
  │
  └── external electrical feed
             │
             ▼
            IT
```

Този model не изключва local backup generation; просто вече не е нужно local backup да бъде единственото обяснение.

## Relation към radio monitoring

S03E05 директно установява, че Silo 1 следи active radio frequencies на другите Silos.

S03E06 добавя втори privileged infrastructure role:
- central radio visibility;
- external IT electrical supply.

Това materially strengthens model-а, че Silo 1 е central infrastructure node, но **не доказва, че Silo 1 = „Гласът“**.

## Safeguard path към Judicial

В същото architectural reasoning safeguard line-ът се отделя като route към Judicial.

Работният model е:

```text
external infrastructure
   ├── electrical feed → IT
   │        ↑
   │     Silo 1
   │
   └── safeguard path → Judicial
```

Epistemic boundary:
- Silo 1 origin е direct-stated за electrical feed-а;
- source-ът на safeguard path-а остава unresolved;
- exact physical nature на safeguard line-а остава unresolved;
- local endpoint при Judicial не е автоматично equal на activation controller.

## Historical reinterpretation

По-ранното evidence за IT power continuity при local outages може да се преинтерпретира чрез external Silo 1 feed.

Това е refinement, не overwrite: старото observation остава валидно; новото evidence предлага конкретен mechanism.
