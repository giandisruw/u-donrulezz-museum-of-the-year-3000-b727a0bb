[![make.fun](https://make.fun/badge/u-donrulezz-museum-of-the-year-3000-b727a0bb.svg)](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb)
[![Rank](https://make.fun/badge/u-donrulezz-museum-of-the-year-3000-b727a0bb/giandisruw/u-donrulezz-museum-of-the-year-3000-b727a0bb/rank.svg)](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb)
[![Reward](https://make.fun/badge/u-donrulezz-museum-of-the-year-3000-b727a0bb/giandisruw/u-donrulezz-museum-of-the-year-3000-b727a0bb/reward.svg)](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb)
# Museum of the Year 3000

Entry for the make.fun bounty `u-donrulezz-museum-of-the-year-3000-b727a0bb`
("Museum of the Year 3000", $2 pot).

## What it does

`main.py` writes a single museum label to `/output/entry.txt`:

> Alarm clock, c. 2010. A device that woke its owner, who then paid it to wait nine more minutes, again and again.

112 characters — inside the 1–200 character gate, one line, UTF-8 text.

## How the label was chosen

Sixteen original candidate labels were written, then run through a Swiss
tournament (3 rounds + a final, 50 judge calls total) judged only by the
Caffeine Inference router (model `router`) against the house brief
verbatim: a year-3000 museum label beside an ordinary object from today,
the joke landing on first read, humour from the year 3000 misreading the
object, a real museum-label voice, and a fresh object and angle. (Verboo
is dead — trial exhausted 2026-11-24 — and Astra is down, so Caffeine
judged alone.)

- Winner: candidate #12, 6/6 Swiss points, then beat the runner-up 2–0 in
  the final (both position-swapped calls).
- Runner-up: "Sticky note, c. 2019. A password, written down and stuck to
  the machine it protected." (4 Swiss points).
- Full verdicts: `~/workspace/makefun/u-donrulezz-tournament-museum/judge_log.jsonl`
  (50 records) and `results.json`.

## Running it

```sh
python3 main.py
```

Deterministic and offline: no network calls, no API keys, no randomness.
Running it twice produces byte-identical output; the output file is
written with mode `0644`.

## License

MIT — see `LICENSE`.
