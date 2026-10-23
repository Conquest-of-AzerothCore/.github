<div align="center">

# Conquest of AzerothCore

**Conquest of Azeroth, rebuilt on [AzerothCore](https://github.com/azerothcore/azerothcore-wotlk) for the World of Warcraft 3.3.5a client.**

[Website](https://coa-development.org/) · [Discord](https://discord.gg/2gmvcRXZTK) · [Source](https://github.com/Conquest-of-AzerothCore/coa-development) · [Report a bug](https://github.com/Conquest-of-AzerothCore/coa-development/issues)

</div>

---

## What is Conquest of AzerothCore?

Conquest of AzerothCore is an independent, open-source reconstruction of the **Conquest of Azeroth** game mode:
Wrath of the Lich King's world played with a roster of entirely new classes, each with its own resources,
specializations and talent trees.

The server is an AzerothCore fork with a dedicated CoA component that speaks the Ascension 3.3.5a client's
protocol and implements its custom classes, character advancement, account-wide collections and systems.

The realm is a **public bug-test server**: it exists to find and fix bugs, and accounts, characters and progress
can be wiped at any time.

## The classes

|   |   |   |
|---|---|---|
| Barbarian | Bloodmage | Chronomancer |
| Cultist | Felsworn | Guardian |
| Knight of Xoroth | Necromancer | Primalist |
| Pyromancer | Ranger | Reaper |
| Runemaster | Starcaller | Stormbringer |
| Sun Cleric | Templar | Tinker |
| Venomancer | Witch Doctor | Witch Hunter |

## What's on the realm

- **Character advancement**: class specializations and talent trees for all 21 classes.
- **Dungeons**: Random Dungeon Finder with Heroic and Mythic difficulties, and Mythic+ keystones.
- **Itemization**: Worldforged items, Mystic Enchants, item and level scaling.
- **World content**: Call Board quests and caches, Manastorm, and High-Risk zones.
- **Collections**: account-wide vanity items and appearances.

## Play and help test

1. Create an account on [coa-development.org](https://coa-development.org/).
2. Join the [Discord](https://discord.gg/2gmvcRXZTK) for the realmlist, client setup and announcements.
3. Found something broken? [Open an issue](https://github.com/Conquest-of-AzerothCore/coa-development/issues)
   with the steps to reproduce it.

## Repositories

| Repository | Purpose |
|---|---|
| [coa-development](https://github.com/Conquest-of-AzerothCore/coa-development) | Server source where all development happens. Pull requests go here. |
| coa-server-live | The exact revision running on the live realm (private). |

Changes are merged into **coa-development** first. Tested revisions are promoted to the live realm and tagged
`live-YYYY-MM-DD`, so every live release can be traced back to a public commit.

## Contributing

1. Fork [coa-development](https://github.com/Conquest-of-AzerothCore/coa-development) and branch from `main`.
2. Follow the conventions in its `AGENTS.md` and `.editorconfig`.
3. Open a pull request against `main`.

## License

The server source is licensed under the [GNU GPL v2](https://github.com/Conquest-of-AzerothCore/coa-development/blob/main/LICENSE),
like AzerothCore it is based on.
