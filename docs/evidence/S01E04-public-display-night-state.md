# S01E04 — Public display night state

**Knowledge boundary:** `S01E04`

## Observation

Public exterior display е показан в normal night-state presentation:

- exterior scene е тъмна;
- tree silhouette остава visible;
- небето съдържа светли точки/звезди.

## What this establishes

Public barren representation е **dynamic**, не immutable daytime still image.

Това е съвместимо с няколко architectures:

1. live camera feed;
2. processed live camera feed;
3. prerecorded/time-indexed визуална sequence;
4. generated/synthetic representation synchronized с internal clock;
5. composite pipeline.

## Relation to S01E03 power-down flash

S01E03 вече доказа, че public display може да покаже радикално различно зелено състояние при изключване на захранването.

S01E04 night state добавя важен constraint:

> нормалният public pipeline също сменя визуалното състояние според контекста/времето.

Това strengthens dynamic-pipeline model-а, но **не authenticates barren exterior като physical reality**.

## Open tests

- star positions repeatable ли са;
- clouds/weather имат ли continuous motion;
- day/night transition smooth/live ли е;
- sensor occlusion/cleaning веднага ли се отразява на display;
- system logs reveal ли source switching.
