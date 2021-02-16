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
- Written to be easily adapted to other variants
- Closed source. Open source is not the right model for Havoc

## Background
I got bored tired of standard(8x8) chess.
And wrote from scratch a new variant engine.

Havoc is improving rapidly as I find more speedups and tricks.
Right now it's much faster than Fairy-Max 5.0b.
But weaker. Hopefully Havoc will be much stronger.

I have decided never publish the source code.
Mayhem will be my last open source contribution.

I might give binaries to testers. 
As I enjoy watching Havoc play.

## Results ( Havoc 0.82 v Fairy-Max 5.0b / 10x8 Capablanca / 10+0.1 ): 
```
Score of Havoc 0.82 vs Fairy-Max 5.0b: 29 - 67 - 4  [0.310] 100
...      Havoc 0.82 playing White: 10 - 39 - 1  [0.210] 50
...      Havoc 0.82 playing Black: 19 - 28 - 3  [0.410] 50
...      White vs Black: 38 - 58 - 4  [0.400] 100
Elo difference: -139.0 +/- 73.3, LOS: 0.0 %, DrawRatio: 4.0 %
Finished match
```

## Credits
Thanks to H.G.Muller for XBoard and Fairy-Max 5.0b
