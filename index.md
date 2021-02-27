# Havoc engine
Gothic Chess Engine. Under heavy development

## Technical
- Written in C++17
- Gothic + Capablanca variants supported
- make() + unmake()
- Object oriented. No globals
- Multithreading
- Opening book support (Not polyglot)
- XBoard protocol
- Bug free movegenerator
- Easy to add other variants
- Closed source. To fight plagiarism

## Background
I got bored of standard(8x8) chess.
And wrote from scratch a new variant engine.

Havoc is improving rapidly as I find more speedups and tricks.
Right now it's much faster than Fairy-Max 5.0b. Around Fairy's level atm.

I have decided never publish the source code.
Taking a break from open source.

I might give binaries to testers. 
As I enjoy watching Havoc play.

## Strength 
Somewhere along 2000 - 2100 ELO on fast time controls

## Gothic Results :
10x8 Gothic / ultra bullet tc
```
Score of Havoc 1.01 vs Fairy-Max 5.0b: 667 - 248 - 85  [0.710] 1000
...      Havoc 1.01 playing White: 349 - 112 - 39  [0.737] 500
...      Havoc 1.01 playing Black: 318 - 136 - 46  [0.682] 500
...      White vs Black: 485 - 430 - 85  [0.527] 1000
Elo difference: 155.1 +/- 22.5, LOS: 100.0 %, DrawRatio: 8.5 %
Finished match
```

## Capa Results :
10x8 Capablanca / ultra bullet tc
```
Score of Havoc 1.02 vs Fairy-Max 5.0b: 633 - 270 - 97  [0.681] 1000
...      Havoc 1.02 playing White: 305 - 151 - 44  [0.654] 500
...      Havoc 1.02 playing Black: 328 - 119 - 53  [0.709] 500
...      White vs Black: 424 - 479 - 97  [0.472] 1000
Elo difference: 132.1 +/- 21.8, LOS: 100.0 %, DrawRatio: 9.7 %
Finished match
```

## Credits
Thanks to H.G.Muller for XBoard and Fairy-Max 5.0b
