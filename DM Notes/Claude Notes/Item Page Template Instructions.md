# Item Page Creation Instructions

## Location
Items should be placed in the `/Items` directory of the vault.

## Properties
- If the entire item should not be known yet to the players, set the `public` flag in the properties to `false`
- Information that should be hidden from players and only visible to the DM should be in `%% %%` comment blocks

## Markdown Format

```md
## Description
[2-3 sentence physical description of the item]

## Mechanics
[2-3 sentences, maybe with bullet points/tables on the mechanics of the item, if applicable]

## Notes
[optional notes on where the item was found, relation to story with wikilinks, etc.]
```

## Example

**File:** `/Items/Bolts of Shadow's Mark.md`

```md
---
public: false
---

## Description

These sinister bolts are crafted from blackened metal that seems to drink in the light around them. Wrapped in shadowy wisps that coil like smoke, each bolt pulses faintly with dark purple energy. When loaded, the crossbow itself grows cold to the touch, and a faint whisper—too quiet to understand—emanates from the bolt's tip.

The fletching appears to be made from raven feathers dipped in something viscous and wrong. Those struck by these bolts report feeling not just pain, but a cold emptiness, as if part of their essence was torn away.

## Mechanics

**Bolt of Shadow's Mark** (Rare Ammunition)

You have 2 bolts with this property. When you fire one of these bolts from a crossbow, make a ranged weapon attack as normal. On a hit, the target takes the crossbow's normal damage plus an additional **4d6 necrotic damage**.

Additionally, until the end of your next turn, the target is wreathed in flickering shadows. The next attack roll made against the marked creature has advantage, as the shadows guide the strike toward vulnerable points.

Once a bolt hits or misses, it crumbles to black ash and cannot be recovered.

## Notes

These bolts appear to be the same dark magic ammunition used by the assassin who ambushed the party on the road to [[Southaven]]. The necrotic energy within them feels similar to the corruption found in the cultists' magic—cold, hollow, and hungry.

[[Momeline Sweetwater|Momeline]] claimed these from the assassin after the party captured him during the ambush on the fourth night of their journey from [[Balandel]].
```

## Key Points

1. **Keep descriptions vivid** - 2-3 sentences focusing on appearance and sensory details
2. **Include mechanics** - Game statistics, rarity, and how the item functions in play
3. **Use proper formatting** - Bold item names and rarities; use bullet points or tables for complex mechanics
4. **Notes are optional** - Use for campaign context, where found, or story connections
5. **Use wikilinks** - Link to NPCs, places, and sessions related to the item
6. **DM-only info** - Use `%% %%` comment blocks for hidden properties or future revelations
7. **Be specific with quantities** - Note limited uses, charges, or consumable nature
8. **Reference D&D standards** - Follow standard item rarity and mechanic conventions
