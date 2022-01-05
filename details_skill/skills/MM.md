# Mimic

A complicated skill. It copies last activated skill data right before the activation.

## Standard Stack

Follows the copied skill.

## Resonance Stack

Follows the copied skill.

## Party Stack

Follows the copied skill.

## Negative Stack

Follows the copied skill.

## Mimic Priority

### Skill Type Mimicking Priority

Skill Type priority is First Order of priority. Any clashes happen in respective priority considered on next priority line.

1. Magic Skills
2. Skill Boost Skills
3. Damage Guard Skills
4. Standard Skills
5. Caching Skills
    a. Alternate Skills
    b. Mutual Skills
    c. Refrain Skills

### Card Position Mimicking Priority

Card Position priority is Final Order of priority. Which is the absolute judgment to consider what card should be prioritized.

Consider unit priority if exists more than one unit.

| 2nd | 1st | 3rd |
|---|---|---|

Unit C have highest precedence for consideration.

After unit precedence considered (if any), card position precedence is considered as well.

| 4th | 2nd | 1st | 3rd | 5th |
|---|---|---|---|---|

Again, further the position, is the highest order/Last In = Mimicked for respective skill.
