# tiny-chess-4kb1

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Sairai1/tiny-chess-4kb1/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Sairai1/tiny-chess-4kb1/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine: 0x88 board, negamax with alpha-beta, iterative deepening, quiescence search, transposition table, killer moves, null-move pruning and late-move reductions. It plays games through the make.fun trial environment and scored ~1461 Elo on the kit's practice trials (trial 0: 1654, trials 1–2: 1364 each).

## Run it

```sh
python3 main.py
```

The engine talks to the trial environment at `MAKEFUN_ENV_URL` (UCI moves over HTTP). `main.py` is the kit-compressed entrypoint (4,078 bytes); the readable source it was packed from is `src.py`.

<sub>Entered on [make.fun](https://make.fun/?ref=y1av4gx4&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
