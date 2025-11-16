# Place Page Creation Instructions

## Location
Places should be placed in the `/Places` directory of the vault.

## Properties
- If the entire place should not be known yet to the players, set the `public` flag in the properties to `false`
- Information that should be hidden from players and only visible to the DM should be in `%% %%` comment blocks

## Markdown Format

```md
## Description
[2-3 sentence physical description of the place]

## Background
[optional description of this place's involvement in the story with wikilinks]
```

## Example

**File:** `/Places/Balandel Courthouse.md`

```md
---
public: true
---

## Description

The Balandel Courthouse is a stately wooden hall built to harmonize with the great trees of the city's civic quarter. Its outer walls are crafted from polished oak and cedar, elegantly carved with flowing motifs of sunbursts, lanterns, and flowering branches—symbols of [[Elandria|Elandria, the Lightbringer]]. Wide windows framed in delicate latticework allow sunlight to spill across its facade, giving the impression that the building itself glows with quiet radiance.

Inside, smooth timber beams arch overhead like the canopy of a forest, while silver-inlaid panels depict scenes of wisdom and mercy from Elandria's teachings. The main chamber is open and airy, its benches arranged in gentle curves rather than rigid lines, fostering a sense of communal judgment rather than harsh authority. Though humble in material, the courthouse exudes dignity, embodying the balance of justice, enlightenment, and harmony with nature.

## Background

The party defended [[Queen Aelra Sylanthiel]] against [[Archdruid Thalwen Myr]] in this courthouse and won in [[Session 24 - The Queen's Trial]].
```

## Key Points

1. **Keep descriptions concise** - 2-3 sentences focusing on physical appearance and atmosphere
2. **Use wikilinks** - Link to other relevant pages using `[[Page Name]]` or `[[Page Name|Display Name]]`
3. **DM-only info** - Use `%% %%` comment blocks for secrets
4. **Sensory details** - Include what the place looks, sounds, smells, or feels like
5. **Background is optional** - Only include if the place has significance to the campaign story
6. **Reference sessions** - Link to specific sessions where important events occurred
7. **Architectural/geographical details** - Help paint a vivid picture of the location
