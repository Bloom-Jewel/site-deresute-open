# Skill Index

## Pure Skills

Pure Skills are skills that is made from simplicity, without mixing with the others.

| |
|:-:|
|SU|
|CU|
|PL|
|CG|
|DG|
|HP|

## Compound Skills

Compound Skills are skills that is combined from several skills altogether. Tradeoff or Requirements may exist to compensate the skill strength itself.

### No Requirements

Compound Skills without Requirements are skills that does not require any kind of requirement or an explicit tradeoff for trying to play the game.

||||||
|:-:|:-:|:-:|:-:|:-:|
|AR|Funny uptime|CU|HP||
|CRD|Funny SU rate|SU|CU||
|TUN||CU|PL||

### With Requirements

Compound Skills with Requirements are skills that requires a condition to be met before activating. Unable to fulfill the condition may result the skill being a dud.

||||||
|:-:|:-:|:-:|:-:|:-:|
|FOC|Monocolor Team|SU|CU||
|SYN|Tricolor Team|SU|CU|HP|
|SYM|Tricolor Team|SB|ENS||

### With Tradeoffs

Compound Skills with Tradeoffs are skills that generally have strong potential, so a Tradeoff is required (at least, to be covered by other skills) to compensate the potential itself.

||||||
|:-:|:-:|:-:|:-:|:-:|
|OL|Consumes HP|SU|CG|HP!|
|CC|Reduces timing window|SU|PL!||


## Multiplexer Style

Compound Skills with Multiplexer Style are skills that have same skill attribute, however only one of them (inside the respective skill) will activate. Usually gated with a specific conditionals.

|Name|Skills|Variants|
|:-:|:-:|:-:|
|ACT|SU/SU|Hold/Flick/Slide|

## Boost Skills

Boost Skills are skills that use a table to check whether how much the skill should be boosted.
Sometimes the table may contain attribute restriction to limit the activation to respective attribute only.

||||
|:-:|:-:|:-:|
|SB|Affects all quantitative skills.|All types|
|ENS|Affects all scoring skills.|Defined types|
|SYM|Affects all quantitative skills.|All types|

## Lookup Skills

Lookup Skills are skills that use a lookup table to determine their currently active skill value during activation time.
The skill strength may vary during activation if there are any changes towards the parameter value itself.

|||
|:-:|:-:|
|SL|Life-based Lookup Table|
|MTF|Param-based Lookup Table|

## Cache Skills

Cache Skills are skills that stores currently strongest active respective skill of each possibilities. Most of their usage correlates around Resonance Stack due to stacking at least the same value of the skill is just doing nothing outside Resonance Stack.

||SU|CU|
|:-:|:-:|:-:|
|ALT|Strong Cache|Down|
|RFR|1:1|1:1|
|MUT|Down|Strong Cache|

## Miscellaneous Skills

Miscellaneous Skills are skills that don't have their values defined explicitly and affects the gameplay in general.

|||
|:-:|:-:|
|DG|Flags the Live Performance to not allow losing HP by any means.|
|MM|Copies skill from Mimic Global Cache.|
|MGC|Copies whole unit skill, and pick the best of each skills within the unit.|
