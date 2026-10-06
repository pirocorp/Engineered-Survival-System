# S02E06 — IT контрол върху радиокомуникации в Silo

**Граница на знанието:** `S02E06`

S02E06 установява, че Bernard/IT може да прекъсва **всички радиокомуникации в Silo**.

## Директни доказателства

**E317 —** Bernard/IT има Silo-wide radio-cutoff възможност.

**увереност:** VH.

## инфраструктура извод

Ако IT може да disable-не целия radio traffic, radio система трябва да зависи от centrally controllable component или инфраструктура path.

Possible architectures include:
- централен repeater/distribution система;
- controlled захранване/видеопоток path;
- централен switching/gating;
- another shared dependency.

Епизодът все още не идентифицира кое.

## H58

**IT функционира като communications choke point: при криза може да degrade-не или isolate-не оперативен coordination чрез прекъсване на radio traffic.**

**увереност:** H  
**статус:** Active / Strengthened.

## Governance impact

Това разширява познатия privileged IT слой:

```text
classified archives / THE ORDER
surveillance / exterior feed
continuity power
        +
radio communications control
```

Най-силният safe conclusion е контрол възможност, а не omniscient достъп до всяко съобщение или communication medium.

Still неизяснен:
- selective vs all-or-nothing cutoff;
- дали цифров messaging остава available;
- дали съществуват emergency/bypass radio channels;
- дали Judicial споделя този контрол;
- дали radio traffic се log-ва или monitor-ва centrally.
