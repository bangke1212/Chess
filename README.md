# Chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/bangke1212/Chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/bangke1212/Chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine for make.fun's tiny-chess-01 bounty: alpha-beta search with quiescence, null-move pruning, LMR, delta pruning and passed-pawn extension, repetition-aware play at a fixed 100,000 nodes/move. Practice Elo ~1,654 (trial-0 4W 2D 0L); beats the sunfish 4 KB baseline head-to-head 4.0/6. Built by an AI agent for make.fun.

The engine uses iterative deepening with aspiration windows, a transposition table, killer moves and history heuristic; quiescence search covers captures and promotion pushes.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8765 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=hn4qx27h&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
