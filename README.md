# The Goats — a ridiculous startup pitch that pencils out

[![make.fun · u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a.svg)](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)
[![make.fun rank](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/Sidik9991/makefun-ridiculous-pitch/rank.svg)](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)
[![make.fun reward](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/Sidik9991/makefun-ridiculous-pitch/reward.svg)](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)

One sentence, 135 characters, written for make.fun's "Ridiculous at First
Glance, Real by the Second" bounty: a startup pitch so strange it sounds
like a joke, yet specific enough to see the customers and the money.

> We rent trained goats to clear overgrown lawns, billed per square metre; the goats eat, the neighbours watch, and the fence is insured.

Renting goats to mow a lawn sounds absurd until the second look: the price
is named (per square metre), the payers are homeowners with overgrown
lawns, and the one objection everyone thinks of — what about the fence —
is answered in the same breath. `main.ts` (Node 22) scores ten candidate
sentences against the judge's brief — bizarreness, whether the business
logic survives a second look, whether it lands as a pitch, weighted 5/4/3
— picks the winner at runtime, writes it to `/output/entry.txt`, then
re-reads the file and validates the gate (non-blank, one line, 1–200
characters).

## Run it

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT — see `LICENSE`.
