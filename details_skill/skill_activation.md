# Skill Activation

## Priority

To understand this, all skill that is activating had their flags checked right before evaluating all activating skills on that moment.

1. Apply Mimic Skill into Additions, if any
2. Skill Boost Skills
4. Damage Guard Skills
6. Normal Skills
8. Cache Skills
    1. Alternate Skills
    3. Mutual Skills
    5. Refrain Skills

Magic Skills are not written explicitly as the way Magic Skill checks is happened every step after Skill Priority Activation.

## Time Limit

Skill Activation will only happen from start of a chart until last 3 seconds of the chart, which may be crucial on some songs like Angel Dream.

## Activation Rate

In general, there are several factors that boosts card activation rate.

- Skill Level, this allows the card to peak about 50% extra bonus from original.
- Skill Potential, this allows the card to add extra rate by flat rate to the skill.
- Song Attribute, this gives an extra 30% rate for matching the attribute.
- Ability Skills, this leader skills gives another extra bump by given variable rate for fitting the criteria if any.

All of those are compiled into one single formula as:
```
(Base Rate + (Max Rate - Base Rate) x (Skill Level - 1) / 9 + Skill Potential) x
  (1 + Attribute Bonus + Leader Bonuses)
```

To help producer needs, some of potential values are set with assumption of Skill Level 10 of the cards.

|確率<br>Rate Text|最高元<br>Rate Value|異/なし<br>0%|同/なし<br>30%|異/あり<br>35%|異/あり<br>40%|異/あり<br>50%|同/あり<br>65%|同/あり<br>70%|同/あり<br>80%|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|中|52.5%|∞|∞|∞|10|9|7|6|4|
|高|60.0%|∞|10|9|8|6|1|0|0|

Notes:
- 異 means "Different", aka "Off-type" cards.
- 同 means "Same", aka "On-type" cards.
- ∞ means "You can't bring this with that condition".
- 0 means "Regardless of Skill Potential, you can bring this".
