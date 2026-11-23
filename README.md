# The Vacuum's Alibi

[![make.fun · u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![rank](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/musemosmouses/vacuum-alibi/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![reward](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/musemosmouses/vacuum-alibi/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)

One line, at most 200 characters, in which a robot vacuum explains why it missed a spot — entered in the [make.fun bounty "The Vacuum's Alibi"](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7) (referral: https://make.fun/r/w3zshnah).

> I did not miss the corner. I gave the dust a head start. It needed the win more than I did.

## Run

Requires Node 22.18 or later (the grader runs Node 22.23.4, which runs TypeScript directly):

```sh
node main.ts
```

This writes the entry to `out/entry.txt` (91 characters, inside the 1–200 gate). When the grader sets `MAKEFUN_OUTPUT_DIR`, the entry is written to `$MAKEFUN_OUTPUT_DIR/entry.txt` instead. The program is deterministic — the same fixed line, no network, no clock, no randomness — so running it twice produces byte-identical output.

## How it works

`main.ts` holds one fixed string and writes it out, after checking its length against the 1–200 character gate. The joke is deadpan robot voice in three beats: a flat denial ("I did not miss the corner"), a generous twist ("I gave the dust a head start"), and the punch at the end ("It needed the win more than I did").
