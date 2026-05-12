# Ash Cat System

## Purpose

Ash exists to make the base feel like a real home.

This is not a large pet system yet. Ash is a tiny emotional feature that supports the core identity of the game:

> Dangerous world outside. Cozy home inside.

## Design rule

Ash should feel discovered, not assigned.

Do not place Ash directly in the main path with a big quest marker. Let curious players notice her through sound, movement, or a small visual clue.

## Discovery

Possible hiding spots:

- under a broken wooden cart
- behind a collapsed wall
- near a ruined fireplace
- inside a hollow tree
- behind tall grass at the camp edge

Soft discovery hint:

```text
You hear a faint meow near the old camp.
```

When found:

```text
A scared cat watches you from the shadows.
```

Interaction:

```text
Pet gently
```

## Trust

Prototype trust system:

```text
Ash Trust: 0/3
```

Trust increases through:

- petting
- feeding simple food item

At 3/3:

```text
Ash seems to trust you now.
Maybe she needs a safe place at the camp.
```

For the prototype, Ash does not need complex follow AI.

Recommended implementation:

```text
Ash befriended -> Ash disappears from wild spot -> Ash appears at camp
```

## Home behavior

Once at camp, Ash can:

- wander in a small radius
- sit near the player bed
- sleep near the campfire
- meow when player approaches
- be petted

Keep the AI simple.

## Cat Bed

The Cat Bed is not crafted immediately from basic materials.

It is a guaranteed first-kill reward from the Bone Warden.

Reason:

> The boss reward becomes personal: we beat the boss and brought something home for Ash.

### Flow

1. Find Ash.
2. Earn trust.
3. Ash appears at camp.
4. Defeat Bone Warden.
5. Receive Cat Bed Blueprint.
6. Build Cat Bed.
7. Ash officially settles into the base.

## Comfort bonus

After Ash has a bed, resting at home gives a tiny bonus:

```text
Cozy Home
Rested buff duration +2 minutes
```

This should be useful but not mandatory.

## Pet safety

Ash should not die permanently.

Rules:

- no permanent pet death
- no combat role for Ash in prototype
- during dangerous events, Ash hides or becomes unavailable
- Ash should create attachment, not punishment

## Later polish: Cat Mischief Event

This is not required for the first implementation, but it is a strong social-media-friendly detail.

### Behavior

1. Ash wanders near a valid table/workbench spot.
2. A hidden `CatMischiefSpot` checks cooldown.
3. A temporary cup prop spawns.
4. Ash plays a paw-swipe animation.
5. Cup falls or animates off the table.
6. Cup despawns after a few seconds.
7. Ash returns to idle.

### Rules

- cosmetic only
- long cooldown
- only when player is nearby
- does not affect real player-built objects
- cup is not saved
- no multiplayer item desync complexity

## Do not add yet

- multiple pets
- dogs
- birds
- owls
- pet combat
- pet inventory
- pet death
- breeding
- pet skill trees
- complex taming chains

## Success test

Ash works if players naturally say:

- “Where is Ash?”
- “Build her bed first.”
- “This base feels more like home now.”
- “Did the cat just knock that cup over?”