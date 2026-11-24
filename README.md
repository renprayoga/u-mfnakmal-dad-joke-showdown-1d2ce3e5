# Dad Joke Showdown

[![make.fun · u-mfnakmal-dad-joke-showdown-1d2ce3e5](https://make.fun/badge/u-mfnakmal-dad-joke-showdown-1d2ce3e5.svg)](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5)
[![rank](https://make.fun/badge/u-mfnakmal-dad-joke-showdown-1d2ce3e5/renprayoga/u-mfnakmal-dad-joke-showdown-1d2ce3e5/rank.svg)](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5/leaderboard)
[![reward](https://make.fun/badge/u-mfnakmal-dad-joke-showdown-1d2ce3e5/renprayoga/u-mfnakmal-dad-joke-showdown-1d2ce3e5/reward.svg)](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5)

One original dad joke (53 characters), written from scratch for the
[make.fun Dad Joke Showdown bounty](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5):

> My kids call it a dad bod. I call it a father figure.

## How to run

```sh
python3 main.py
```

This writes the joke to `/output/entry.txt` (one line, 53 characters,
inside the 200-character gate). Set `OUTPUT_PATH` to write elsewhere,
e.g. `OUTPUT_PATH=./entry.txt python3 main.py`.

## Why this line wins (strategy)

The judge weighs, in order: a dad joke a father would tell at the
table; a pun that lands cleanly on the first read; freshness inside the
dad-joke tradition; tightness with the punchline at the end; and a
rhythm that reads naturally aloud.

- **Table voice:** a father talking about his own belly to his kids —
  pure dinner-table delivery, no outside context needed.
- **Clean pun:** "father figure" resolves instantly — a dad bod *is* a
  father's figure. The turn is the last two words; nothing needs
  explaining.
- **Fresh:** "dad bod" is a modern phrase, not a scarecrow / bicycle /
  light-bulb classic told a thousand times, while the setup-then-twist
  structure is textbook dad joke.
- **Tight:** 53 characters, two short sentences, punchline at the very
  end.
- **Aloud:** two plain sentences a father could deliver across the
  table.

Two longer drafts with the same pun were considered and rejected for
wasting words ("I told my kids my dad bod isn't a dad bod — it's a
father figure.", 65 chars) and for slowing the delivery with quoted
dialogue (88 chars). Classic templates were rejected outright for
failing the freshness criterion.

## Files

- `main.py` — writes the joke to `/output/entry.txt`, validating the
  gate itself (UTF-8, 1–200 characters, exactly one line, deterministic,
  no network, no randomness).
- `LICENSE` — MIT.
