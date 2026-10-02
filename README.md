# numinia-archive-feed

What Numen Games' automation finds, **unreviewed**.

Machines write here without asking. Nothing here is a record of the archive:
a call, a lead or a figure becomes one only when a person reads it and a
reviewed pull request writes it into
[numinia-archive](https://github.com/numengames/numinia-archive). The archive
reads this repository and shows what it finds marked *unreviewed*.

The rule is `AUT-069` in *Who may change what* (`STD-017`), on
[numinia.org](https://numinia.org/standards/std-017-who-may-change-what).

## What is here

| Path | Written by | What it holds |
|---|---|---|
| `radar/board.json` | the tender radar, every half hour | Public tenders and grant calls ranked by chance. Only what passes the filter: chance *alta* or *media*, or *baja* when the fit is real and something could unlock it. The discards are not published. |

Each radar item: `id`, `source`, `kind`, `title`, `buyer`, `url`, `closes`,
`amount`, `buys`, `fit`, `chance`, `blocker`, `why`, `next`, `read_from`,
`updated`, and `in_archive` when the archive already holds it as a record.
The text is in Spanish, as the radar writes it.

## What is never here

- **A person's name**, an e-mail or a phone. Every item is read by the
  archive's own detector before it is written (`OPP-006`); an item that trips
  it is held back.
- A downloaded document. The `url` points to the publisher's own page.
- A client's name. The radar reads public calls only.

## Licence

The data is [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/):
the calls are public, the ranking is ours, and both are given away.
