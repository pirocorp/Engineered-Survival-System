# S02E06 — IT control върху radio communications в Silo

**Knowledge boundary:** `S02E06`

S02E06 установява, че Bernard/IT може да прекъсва **всички radio communications в Silo**.

## Direct evidence

**E317 —** Bernard/IT има Silo-wide radio-cutoff capability.

**Confidence:** VH.

## Infrastructure inference

Ако IT може да disable-не целия radio traffic, radio system трябва да зависи от centrally controllable component или infrastructure path.

Possible architectures include:
- central repeater/distribution system;
- controlled power/feed path;
- central switching/gating;
- another shared dependency.

Епизодът все още не идентифицира кое.

## H58

**IT функционира като communications choke point: при криза може да degrade-не или isolate-не operational coordination чрез прекъсване на radio traffic.**

**Confidence:** H  
**Status:** Active / Strengthened.

## Governance impact

Това разширява познатия privileged IT layer:

```text
classified archives / THE ORDER
surveillance / exterior feed
continuity power
        +
radio communications control
```

Най-силният safe conclusion е control capability, а не omniscient access до всяко message или communication medium.

Still unresolved:
- selective vs all-or-nothing cutoff;
- дали digital messaging остава available;
- дали съществуват emergency/bypass radio channels;
- дали Judicial споделя този control;
- дали radio traffic се log-ва или monitor-ва centrally.
