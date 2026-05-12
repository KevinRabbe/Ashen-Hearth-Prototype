# Ashen Hearth Prototype

Ashen Hearth Prototype is a small 1–4 player co-op action RPG prototype focused on fighting, looting, building, and turning a broken camp into a real home.

The first goal is not a full game. The first goal is a 20–40 minute playable demo that proves the core loop:

```text
Fight -> Loot -> Build -> Upgrade -> Boss -> Trophy -> Home -> Sleep -> Next Day
```

## Demo promise

Players rebuild a ruined camp, find a scared cat named Ash, fight through cursed forest ruins, collect materials and blueprints, defeat the Bone Warden, bring home a trophy, build Ash a cat bed from the boss reward, and sleep to begin the next day.

## Core pillars

1. **RPG fighting** - simple but satisfying third-person action combat.
2. **Meaningful building** - the base is not just storage; it supports progression and emotional ownership.
3. **Loot that feeds home** - enemies and bosses drop materials, blueprints, trophies, and home upgrades.
4. **Home feeling** - beds, trophies, firelight, and Ash make the base feel alive.
5. **Small playable scope** - no MMO systems, no huge world, no feature creep.

## Current target

Build a single-player greybox first, then test early co-op once the basic loop works.

First playable milestone:

```text
Player moves -> attacks enemy -> enemy dies -> drops loot -> player picks it up -> player places a building piece -> player sleeps in bed.
```

## Tech stack

- Engine: Godot 4 .NET
- Language: C#
- Version control: Git + GitHub
- First networking target: host/client co-op later, not at the beginning
- Art style for prototype: placeholder/greybox first

## Documentation

- [Prototype Design](docs/prototype_design.md)
- [Demo Flow](docs/demo_flow.md)
- [Ash Cat System](docs/ash_cat_system.md)
- [Roadmap](ROADMAP.md)
- [Todo](TODO.md)

## Status

Prototype planning phase.