# Prototype Design

## Working title

**Ashen Hearth Prototype**

## Current scope

A 20–40 minute 1–4 player co-op action RPG demo. The first implementation starts single-player, then moves into early co-op testing once the basic loop works.

This prototype is not an MMO, not a full survival game, and not a huge open world. It exists to prove one core idea:

> Fighting outside should feed the home base, and the home base should make fighting feel more meaningful.

## Core loop

```text
Fight -> Loot -> Build -> Upgrade -> Boss -> Trophy -> Home -> Sleep -> Next Day
```

## Emotional loop

```text
Danger outside -> return home -> make home safer/cozier -> prepare again -> go back out
```

## Demo fantasy

Players are a small adventurer group rebuilding a ruined camp on the edge of cursed forest ruins. They fight skeletons and corrupted creatures, gather materials and blueprints, upgrade a small armory, defeat the Bone Warden, mount its trophy, build a bed for Ash the cat, and sleep to begin the next day.

## Zone

### Cursed Forest Ruins

A dark forest zone with broken stone ruins, dead trees, corrupted wildlife, old camp remains, and one boss shrine.

The zone supports:

- basic wood and stone building materials
- skeleton enemies
- corrupted animal enemies
- cursed iron materials
- ruined stone building pieces
- bone-themed decoration pieces
- early RPG fantasy mood

## Player

### Prototype abilities

- third-person movement
- sprint
- jump
- dodge roll placeholder
- light attack
- heavy attack
- block
- interact
- pick up loot
- place building pieces
- sleep/rest

### Prototype stats

- health
- stamina
- damage
- armor

No complex attributes yet.

## First weapon

### Rusted Sword and Shield

The first weapon set should support:

- light attack
- heavy attack
- block
- simple stagger feedback

Only one weapon is needed for the first version. One decent weapon is better than many unfinished weapons.

## Enemies

### Bone Thrall

Basic skeleton enemy.

Purpose:

- teaches melee combat
- easy to kill
- drops basic materials

Drops:

- bone scraps
- cursed coins
- ruined wood
- small blueprint chance

### Corrupted Wolf

Fast animal enemy.

Purpose:

- forces movement and dodging
- creates pressure in the forest area

Drops:

- corrupted hide
- fangs
- meat/fur material
- rare banner/cosmetic chance

### Gravebound Knight

Elite skeleton enemy.

Purpose:

- slower but stronger
- teaches blocking and timing
- guards chests or boss path

Drops:

- cursed iron
- cracked armor plates
- higher blueprint chance

## Boss

### The Bone Warden

A large skeletal knight guarding the ruined shrine.

Attacks:

- heavy slam
- sweeping attack
- short charge
- ground curse area
- summon 1–2 Bone Thralls

Guaranteed first-kill rewards:

- Bone Warden Trophy
- Cat Bed Blueprint
- Cursed Iron Core
- one random building blueprint

The Cat Bed Blueprint is important because it connects the boss reward to Ash and the home feeling.

## Building

### Basic pieces

- wooden foundation
- wooden floor
- wooden wall
- wooden half wall
- doorway
- window wall
- wooden roof
- stairs
- beam
- pillar
- door

### Utility pieces

- campfire
- torch
- chest
- workbench
- armory station
- player bed
- trophy mount

### Unlockable pieces

- skull torch
- bone fence
- ruined stone arch
- cursed banner
- bone pillar
- Warden brazier
- cat bed

## Base systems

### Workbench

Basic building and crafting hub.

### Armory

First meaningful room/station system.

Function:

- repair/upgrade sword
- use cursed iron and bone materials
- gives gameplay value to the base

### Player Bed

Function:

- respawn point
- rested buff
- sleep-to-next-day loop

The bed should feel like a home object, not a menu button.

### Trophy Mount

Function:

- mount boss trophy
- unlock new pieces or small buffs
- make boss kills visible in the home base

## Ash the Cat

Ash is a small emotional system that makes the base feel alive.

Core flow:

1. Find Ash slightly hidden near camp or forest edge.
2. Pet/feed Ash until trust reaches 3/3.
3. Ash comes to the base but has no proper bed yet.
4. Defeat the Bone Warden.
5. Boss drops Cat Bed Blueprint.
6. Build Cat Bed.
7. Ash sleeps at home and gives a tiny comfort bonus.

## Demo ending

The best demo ending is:

1. Defeat Bone Warden.
2. Return home.
3. Mount Bone Warden Trophy.
4. Build Ash's Cat Bed.
5. Ash sleeps in her bed.
6. Players sleep in their beds.
7. Day 2 begins.

## Do not add yet

These are later ideas, not demo features:

- MMO systems
- public servers
- PvP
- factions
- huge skill trees
- 20+ weapons
- 20 biomes
- complex farming
- trading economy
- mounts
- boats
- multiple pets
- pet combat
- pet death
- breeding
- full NPC towns
- large procedural world

## Success test

The prototype succeeds if playtesters say things like:

- “Can we run it again?”
- “Can I build the base differently?”
- “Can we farm that blueprint?”
- “Ash makes the base feel like home.”
- “The boss reward felt worth it.”