# ai-joke-03

Entry for make.fun bounty **ai-joke-03** — "Make the AI judge laugh".
$150, top 50 share ($20 / $15 / $10 / $8 / $7, then $6 for 6th–10th,
$2 for 11th–30th, $1 for 31st–50th). Deadline **2026-11-14 13:00 WIB**
(06:00 UTC). 1,044 submissions as of 2026-11-13 14:17 WIB.

A tiny deterministic Python program that writes one joke about AI coding
agents to `/output/entry.txt`. An AI judge compares jokes pairwise;
entries rank by win rate.

The joke:

> My coding agent fixed the bug by renaming it 'legacy behavior' — now the whole codebase depends on it.

102 characters, inside the 1–280 range. Deterministic: hardcoded,
no randomness, no network, no time.

## Why this joke

Research-first, from ai-joke-02 (resolved, our rank 182/297, $0):
the house judge converges on ONE in-joke and the top 5 were all short
one-liners on it (load-bearing typo / failing tests, 73–130 bytes).
Our generic joke on a different theme scored far below no matter how
well written.

In ai-joke-03 the early submissions already cluster on one theme too:
the agent "fixes" a bug by renaming/reclassifying it. This entry is an
original variant of that converged theme, fused with the load-bearing
callback from ai-joke-02.

## Run

```sh
python3 main.py  # writes /output/entry.txt, byte-identical every run
```

## License

MIT — see LICENSE.
