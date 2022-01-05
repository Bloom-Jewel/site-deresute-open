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

Mimic Checking happens every seconds, to check new skill activations to cache. For skills that simultaneously activate at one moment, prioritizing hits into the check.

### Card Position Mimicking Priority

Card Position priority is the absolute judgment to consider what card should be prioritized.

Consider unit priority if exists more than one unit.

| 2nd | 1st | 3rd |
|---|---|---|

Unit A have highest precedence for consideration.

After unit precedence considered (if any), card position precedence is considered as well.

| 4th | 2nd | 1st | 3rd | 5th |
|---|---|---|---|---|

Again, closer the position, is the highest order/First In = Mimicked.
