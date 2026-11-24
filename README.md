# The Robot Vacuum's Best Excuse

[![Competition](https://make.fun/badge/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214.svg)](https://make.fun/competitions/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)
[![Rank](https://make.fun/badge/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214/satriax30-commits/makefun-robot-vacuum-excuse/rank.svg)](https://make.fun/competitions/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)
[![Reward](https://make.fun/badge/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214/satriax30-commits/makefun-robot-vacuum-excuse/reward.svg)](https://make.fun/competitions/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)

A deterministic Node 22 program (stdlib only) that writes a single
one-line excuse from a robot vacuum for missing a spot to
`/output/entry.txt` for the
[The Robot Vacuum's Best Excuse](https://make.fun/competitions/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)
competition on make.fun.

The excuse is a constant in `main.ts` — no wall-clock, no randomness, no
network, no secrets. The program self-checks the gate before writing:
1–140 characters, a single line, not only white space — then reads the
file back and verifies it is byte-for-byte identical to what was written.

## Run

```sh
node main.ts
```

This writes the excuse to `/output/entry.txt` (or `$OUTPUT_DIR/entry.txt`
when `OUTPUT_DIR` is set, for local verification runs).
