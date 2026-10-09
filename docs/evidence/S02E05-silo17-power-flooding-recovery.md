# S02E05 — Независимо захранване на IT, наводняване и възстановяване на помпата в Silo 17

**Knowledge boundary:** `S02E05`

## Independent IT power

Оцелелият от Silo 17 заявява, че IT има собствено независимо електрозахранване, идващо от външен източник, а не от нормалния път през генератора на Silo.

Това директно обяснява по-рано наблюдаваното остатъчно захранване на IT след колапса на целия Силоз.

## Последователност на отказите при наводняването

Оцелелият описва:

```text
rebellion
  ↓
pump on Level 144 destroyed
  ↓
intent: flood Mechanical
  ↓
water continues rising
  ↓
generator not repaired in time
  ↓
generator floods / normal power fails
  ↓
water continues rising into present
```

## Recovery plan

Оцелелият иска Juliette да ремонтира помпа, която може да спре/забави покачващата се вода, и да я захрани от IT.

Следователно независимото захранване на IT не служи само за осветлението в трезора; то потенциално може да захранва избрана критична инфраструктура за възстановяване.

## H54

**Инфраструктурата на IT/трезора има независим външен път за захранване, достатъчно устойчив да преживее загубата на нормалното електрогенериране в Силоза и потенциално да поддържа аварийни товари за възстановяване.**

**Confidence:** H  
**Status:** Strongly Strengthened

Still unresolved:
- source location;
- generation technology;
- capacity;
- routing;
- дали architecture е standardized across Silos;
- дали `external/outside` означава физически извън Силоза или външно спрямо нормалната му вътрешна електрическа мрежа.
