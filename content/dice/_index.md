---
Title: Dice
---

Perform complex dice rolling.
Cog Version: 2.0.0
## Commands
- {{% commandref dice "Perform die roll based on a dice formula." %}}

{{% command dice "Perform die roll based on a dice formula." "<roll>" %}}
The [PyHedrals](https://github.com/StarlitGhost/pyhedrals) library is used for dice formula parsing.

Use the link above to learn the notation allowed. Below are a few examples:

- `2d20kh` - Roll 2d20, keep highest die (e.g. initiative advantage)
- `4d4!+2` - Roll 4d4, explode on any 4s, add 2 to result
- `4d6rdl` - Roll 4d6, reroll all 1s, then drop the lowest die
- `6d6c>4` - Roll 6d6, count all dice greater than 4 as successes
- `10d10r<=2kh6` - Roll 10d10, reroll all dice less than or equal to 2, then keep the highest 6 dice

Modifier order does matter, and usually they allow for specifying a specific number or number ranges after them.