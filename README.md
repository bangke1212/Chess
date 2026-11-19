# tiny-chess-01

A chess engine in 4 KB of Python for the make.fun tiny-chess-01 bounty.

`main.py` is the entrypoint (packed with `makefun compress` from the
readable source). It is a 0x88 negamax alpha-beta engine: transposition
table, killer moves, MVV-LVA ordering, quiescence, null-move pruning,
late-move reductions, check extensions, and a tapered piece-square
evaluation with a bishop-pair bonus. Fixed 100,000 nodes per move,
fully deterministic, standard library only, no model calls.

Run: `python3 -P -s main.py` with `MAKEFUN_ENV_URL` set.
