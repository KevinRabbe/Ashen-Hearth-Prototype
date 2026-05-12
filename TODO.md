# Todo

## Current focus

Start with **Milestone 0: Project setup** and **Milestone 1: Core toy**.

Do not implement the full demo immediately.

## Milestone 0: Project setup

- [ ] Install Godot 4 .NET version
- [ ] Create new Godot C# project
- [ ] Place project under `GodotProject/`
- [ ] Create folder structure
- [ ] Create test scene
- [ ] Add input actions
- [ ] Commit clean project setup

## Recommended input actions

- [ ] move_forward
- [ ] move_back
- [ ] move_left
- [ ] move_right
- [ ] jump
- [ ] sprint
- [ ] dodge
- [ ] attack_light
- [ ] attack_heavy
- [ ] block
- [ ] interact
- [ ] build_place
- [ ] build_rotate
- [ ] open_inventory

## Milestone 1: Core toy

Goal:

```text
Player moves -> attacks enemy -> enemy dies -> drops loot -> player picks up loot -> player places one building piece -> player sleeps in bed.
```

### Player

- [ ] Create player scene
- [ ] Add CharacterBody3D
- [ ] Add camera pivot
- [ ] Add camera
- [ ] Implement third-person movement
- [ ] Implement sprint
- [ ] Implement jump
- [ ] Add dodge placeholder
- [ ] Add stamina component
- [ ] Add health component

### Combat

- [ ] Add basic sword scene/model placeholder
- [ ] Add light attack input
- [ ] Add hitbox area
- [ ] Add damage interface/component
- [ ] Add enemy hurtbox
- [ ] Add simple hit feedback

### Enemy

- [ ] Create dummy enemy scene
- [ ] Add enemy health
- [ ] Add simple idle/chase behavior
- [ ] Add enemy death
- [ ] Add loot drop on death

### Loot and inventory

- [ ] Create loot pickup scene
- [ ] Add pickup interaction
- [ ] Add simple inventory dictionary/counter
- [ ] Display temporary inventory debug text

### Building

- [ ] Create one wall or floor piece
- [ ] Add building placement preview
- [ ] Add place action
- [ ] Keep it simple: no full snapping system yet unless easy

### Bed

- [ ] Create player bed scene
- [ ] Add interact prompt
- [ ] Sleep fade placeholder
- [ ] Set respawn point
- [ ] Start Day 2 placeholder

## Milestone 2+ later

- [ ] Bone Thrall
- [ ] Corrupted Wolf
- [ ] Gravebound Knight
- [ ] Armory station
- [ ] Blueprints
- [ ] Trophy mount
- [ ] Ash discovery
- [ ] Bone Warden boss
- [ ] Cat Bed Blueprint
- [ ] Cat Bed
- [ ] Day 2 summary
- [ ] Early co-op sync test

## Cut / Later list

Put tempting ideas here instead of adding them to the demo.

- multiple pets
- dogs
- birds/owls
- pet combat
- MMO systems
- PvP
- factions
- farming
- economy
- mounts
- boats
- large open world
- procedural generation
- many weapon classes
- full skill tree