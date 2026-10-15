# Dying Light: Round Cards

**Status: design only. Not playable, not built, not tested yet.**

A solo mashup of **Dying Light** and **ROUNDS**. You play normal Dying Light. Every time you level up you also pick one of three ROUNDS cards, and the cards stack for the rest of your run.

## How it's meant to work

- **Host game:** Dying Light (the mod installs into its `DW` folder).
- **Companion game:** ROUNDS. Card names, art and text are read from the player's own ROUNDS install. No ROUNDS files are included in this project.
- **Level-up reward:** a random pick-1-of-3 from 20 cards in the first version. Effects are translated into Dying Light stats (health, damage, jump height and so on), some with trade-offs.
- **Players:** solo only in the first version.

## Requirements (planned)

You need your own copies of both Dying Light and ROUNDS. Nothing from either game is redistributed here.

## What's in this repo

- `dl-rounds-design-sheets.json`: the draft design sheets (cards, game hooks, listing text, and an open-items list). Everything in them is unverified until checked against the real game files.

## Roadmap

1. Check the sheets against the installed Dying Light scripts and the ROUNDS files.
2. Build the first playable version and test it in the game.
3. Package it and publish it on [Melty](https://melty.gg).

## License

Not chosen yet.
