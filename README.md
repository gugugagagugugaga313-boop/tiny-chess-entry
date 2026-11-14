# tiny-chess-01 entry

A 4 KB Python chess engine: 0x88 board, alpha-beta + quiescence search,
transposition table, killer moves, piece-square tables. Fixed node budget
per move, fully deterministic. Plays the make.fun environment protocol
via `main.py`. `engine.py` is the readable source; `main.py` is produced
by `makefun compress` and is the only file the grader runs.
