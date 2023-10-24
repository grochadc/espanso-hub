# Polyhedral Dice
Use colon `:` and dice notation to roll that dice. 
Example: `:1d4` turns into `[2]` a `d4` result.

Available dice: `d4`, `d6`, `d10`, `d20`

## Multiple Dice:

You can roll 2 on the dice `d10` and `d20`.
Example: `:2d10` turns into `[[5],[2]]` two `d10` results.

For the moment three or more multiple dice are not yet available. More double-dice options coming.


## Percentile (%)
Use `:d%` to get a random 10ths digit (00-90). 
Use this with the result of a `1d10` to get a `d100`.
Example: `d%` => 70 and `1d10` => 2 ; `d100` => 72 

## Fudge Dice
Use `:dF` to roll a Fudge dice with a result between `[blank]`, `[-]` or `[+]`

# Other RPG Systems and Oracles

## Caltrop Core
Simply write `:caltrop` to get a generic Caltrop Core result: Absolute Success. You get what you want — and more.

## Einzelmaus
Sparks
Write `:einzspark` to get a Spark table result: [action: strive; subject: honor].
You can also get sparks separately by writing `:einzsubject` reason or `:einzaction` vanquish.

## Mausritter
NPC Reaction
Write `:mausreaction` to get an NPC Reaction [**Unfriendly**. How can they be appeased?]


Version 0.1.2
