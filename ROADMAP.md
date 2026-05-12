# Roadmap

## Rule

Every feature must support the first playable demo loop.

If a feature does not help prove the loop, it goes into `Later`.

Core loop:

```text
Fight -> Loot -> Build -> Upgrade -> Boss -> Trophy -> Home -> Sleep -> Next Day
```

## Milestone 0: Project setup

Goal: create a clean Godot 4 C# project structure.

Tasks:

- create Godot 4 .NET project
- add base folders
- commit clean project files
- add placeholder test scene
- add basic input map

Suggested folders:

```text
GodotProject/
  Scenes/
    Player/
    Enemies/
    Building/
    Items/
    UI/
    World/
    Demo/
  Scripts/
    Core/
    Player/
    Combat/
    Enemies/
    Inventory/
    Loot/
    Building/
    Crafting/
    Base/
    Save/
    Multiplayer/
  Data/
    Items/
    Enemies/
    BuildingPieces/
    LootTables/
```

## Milestone 1: Core toy

Goal: prove the smallest possible version of the game.

Required loop:

```text
Player moves -> attacks enemy -> enemy dies -> drops loot -> player picks up loot -> player places one building piece -> player sleeps in bed.
```

Features:

- third-person movement
- camera
- health component
- stamina component
- basic sword attack
- one dummy enemy
- simple damage system
- enemy death
- loot drop
- pickup interaction
- tiny inventory counter
- one placeable building piece
- player bed with sleep interaction

## Milestone 2: Combat slice

Goal: make fighting readable and repeatable.

Features:

- light attack
- heavy attack
- block
- dodge roll placeholder
- Bone Thrall enemy
- Corrupted Wolf enemy
- Gravebound Knight elite
- basic loot tables
- hit feedback
- death feedback

## Milestone 3: Building slice

Goal: make the base useful and pleasant to build.

Features:

- foundation
- floor
- wall
- doorway
- window wall
- roof
- stairs
- beam/pillar
- door
- torch
- chest
- workbench
- armory
- player bed
- trophy mount

## Milestone 4: Progression slice

Goal: connect combat rewards to building and upgrades.

Features:

- armory sword upgrade
- basic materials
- rare blueprint unlocks
- trophy reward unlocks
- rested buff
- sleep-to-next-day loop

## Milestone 5: Ash slice

Goal: make the base feel like home.

Features:

- hidden Ash discovery
- pet/feed interaction
- trust 0/3 to 3/3
- Ash moves to camp
- Cat Bed Blueprint from boss
- Cat Bed building piece
- Cozy Home bonus
- simple home wandering/sleeping behavior

Optional polish later:

- Cat Mischief Event with temporary cup prop

## Milestone 6: Demo flow

Goal: assemble the full 20–40 minute demo.

Features:

- broken camp start
- forest path
- cursed ruins area
- loot chests
- boss shrine
- Bone Warden boss
- boss trophy
- Cat Bed reward
- Day 2 ending

## Milestone 7: Early co-op test

Goal: test whether the architecture survives multiplayer.

Features:

- host/client connection
- synced player movement
- synced damage
- synced enemy death
- synced loot pickup
- synced building placement
- synced bed/sleep vote

## Later

Do not build these before the first demo works:

- MMO systems
- dedicated servers
- PvP
- factions
- big open world
- procedural world generation
- many weapons
- deep skill trees
- multiple pets
- pet combat
- farming
- economy
- mounts
- boats
- NPC towns
- mod support
- huge building set library