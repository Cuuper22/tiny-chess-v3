# tiny-chess-v3
A 4 KB Python chess engine for the make.fun tiny-chess bounty.
main.py is a three-line unpacker plus a raw-deflate, base85 payload packed from our own engine source.
The engine: 10x12 mailbox move generation, tapered piece-square evaluation, PVS alpha-beta with TT, null move, LMR, killers, history and quiescence.
It searches a fixed node budget (no clock), so every move is deterministic, and plays the env's /game and /move loop.
MIT licensed (see LICENSE).
