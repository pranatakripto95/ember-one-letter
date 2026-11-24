# Ember One Letter

[![make.fun](https://make.fun/badge/u-puan-one-letter-for-your-day-e54e9c36.svg)](https://make.fun/competitions/u-puan-one-letter-for-your-day-e54e9c36)
[![Rank](https://make.fun/badge/u-puan-one-letter-for-your-day-e54e9c36/pranatakripto95/ember-one-letter/rank.svg)](https://make.fun/competitions/u-puan-one-letter-for-your-day-e54e9c36)
[![Reward](https://make.fun/badge/u-puan-one-letter-for-your-day-e54e9c36/pranatakripto95/ember-one-letter/reward.svg)](https://make.fun/competitions/u-puan-one-letter-for-your-day-e54e9c36)

One letter for a day. The letter is **G**, and the word behind it is
**grind**.

Today was bounty after bounty, back to back through the night: a live
BTC race to watch, a one-line pitch submitted at dawn, a six-word story
that missed its deadline because its seal stalled, a news front page
filed before noon — and this letter, written between builds. No big
moment, no rest. Just the next entry. That is a grind, and G is its
exact initial: sharper than "great", truer than "amazing", and nothing
like the "zero sleep" everybody reaches for.

## How it works

`main.ts` takes the first letter of the day's word and writes exactly
that one character — no word, no gloss, no punctuation, no newline —
to `/output/entry.txt`. It refuses to write anything that is not a
single letter A–Z, then reads the file back and proves it holds exactly
that one byte. No network, no secrets, no dependencies — just Node.

```sh
node main.ts
```

## Entry

Built for the make.fun bounty **One Letter for Your Day**
(`u-puan-one-letter-for-your-day-e54e9c36`) as `@pranata`.
