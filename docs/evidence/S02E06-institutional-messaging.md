# S02E06 — institutional digital messaging и communication tiers

**Knowledge boundary:** `S02E06`

## Директни доказателства

Terminal в Sheriff Department видимо включва `DIRECT MESSAGING`.

Inbox-ът съдържа departmental и named senders, включително примери от:
- IT;
- Office of HR;
- Mechanical;
- individual named users.

Втори frame показва реален two-way conversation с named contact.

Това установява функционираща digital messaging system поне за част от institutional users.

## What this changes

По-ранното използване на couriers вече не може да се обяснява просто с "the Silo has no digital messaging".

Текущият model е:

```text
physical couriers
    ↳ broad/general delivery
    ↳ can carry physical material
    ↳ access не зависи от terminal entitlement

institutional digital messaging
    ↳ departments + named users
    ↳ interactive two-way messages
    ↳ endpoint/access population остава неизвестна

radio
    ↳ operational voice traffic
    ↳ IT can disable it centrally
```

## H20 refactor

**Prior direction:** inter-level communication е ограничена в controlled channels.

**След S02E06:** constraint-ът се моделира по-добре като **selective access to communication technologies**, а не като липса на тези technologies.

Digital access за ordinary residents остава unproven.

## H56

**Silo използва multiple parallel communication tiers с различни access и controllability: physical couriers, institutional digital messaging и radio.**

**Confidence:** H  
**Status:** Strongly Strengthened / Refactored спрямо prior communication-control model.

## Open boundaries

Do not yet assume:
- всеки resident има digital account;
- всеки department има equal access;
- digital messages са private;
- IT автоматично чете всички messages;
- couriers съществуват специално за evade-ване на surveillance.

Това остават testable hypotheses.
