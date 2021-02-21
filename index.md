# Havoc engine
Gothic Chess Engine. Under heavy development.

## Technical
- Written in C++17
- Gothic + Capablanca variants supported
- make() + unmake()
- Object oriented. No globals
- Multithreaded
- XBoard protocol
- Bug free movegenerator
- Written to be flexible for other variants
- Closed source. Open source is not the right model for Havoc

## Background
I got bored of standard(8x8) chess.
And wrote from scratch a new variant engine.

Havoc is improving rapidly as I find more speedups and tricks.
Right now it's much faster than Fairy-Max 5.0b. Around Fairy's level atm.

I have decided never publish the source code.
Taking a break from open source.

I might give binaries to testers. 
As I enjoy watching Havoc play.

## Results:
10x8 Capablanca / ultra bullet tc
```
Score of Havoc 1.0 vs Fairy-Max 5.0b: 581 - 307 - 112  [0.637] 1000
...      Havoc 1.0 playing White: 270 - 175 - 55  [0.595] 500
...      Havoc 1.0 playing Black: 311 - 132 - 57  [0.679] 500
...      White vs Black: 402 - 486 - 112  [0.458] 1000
Elo difference: 97.7 +/- 21.0, LOS: 100.0 %, DrawRatio: 11.2 %
Finished match
```

## Credits
Thanks to H.G.Muller for XBoard and Fairy-Max 5.0b
