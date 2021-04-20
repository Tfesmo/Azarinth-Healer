# Azarinth-Healer
## https://www.royalroad.com/fiction/16946/azarinth-healer
## https://www.patreon.com/m/1821265/posts

This is a project to track stats/numbers for Azarinth Healer.
Minus the effective health/mitigation calculations, everything should be accurate from what I can find.

How to read the stat sheet:

Hopefully most of this is fairly intuitive.  Here's the custom areas:

Stats increased by variable skills have the final value shown in brackets
```
Int: 1601 [23,935.0]
```

The regen block is %/sec [amount/sec] [seconds from 0 to full]
```
hp/sec:  0.32% [86.2] [317.1 seconds]
mp/sec:  0.33% [341.3] [307.7 seconds]
w/Med:   0.40% [422.1] [248.8 seconds]
```

Effective Health, see: https://github.com/Tfesmo/Azarinth-Healer/blob/main/references/effective_health.txt
```
Mitigation:       98.004%     [hp x 50.16]
Effective Health: 1,491,021.0 [hp x 97.30]
```

The multiplier after each class skill name is the multiplier it gets from class magic increases
```
3-30 Azarinth Awakening       x9 [85.0% => 765.0% Resilience, Speed, Intelligence and Strength]
```
Azarinth Awakening is Body Enhancement, which is +800%.  With a base of 100% that's a nine times multiplier
The stat is shown even for skills without variable numbers to help highlight bonuses

Resistance information is based on numbers given around chapters 396-405, with some extrapolation
```
2-1   [26% - 42%] Blight Resistance
```
This means a minimum of 26% no matter how high the opponent spell, and a reduction of 42% assuming she's attacked by a 2-1 Blight spell
Azarinth Healer wiki has additional details

From Illea's skill that increases ash density based on resistances
```
Ash Density: 41 x 5% = 205%
```

The bottom section is defensive buffs that don't make sense to add to effective health
