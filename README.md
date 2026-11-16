# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/dzulqarnainfaisal/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/dzulqarnainfaisal/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,096 bytes of Python: 0x88 board, negamax alpha-beta with quiescence search, a Zobrist transposition table, MVV-LVA and killer move ordering, and a deterministic adaptive node budget by game ply (45,000 opening, 90,000 middlegame, 55,000 endgame) so no move is slow on a shared CPU. No clock, no randomness, fully deterministic. Practice Elo 1451 in both practice trials (beats the depth-2, depth-3 and depth-4 house rungs consistently; mean think about 1.7 s a move, worst about 3.3 s).

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=k2fmwcbe&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
