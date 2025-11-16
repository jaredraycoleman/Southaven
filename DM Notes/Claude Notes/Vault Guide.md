# The Heroes of Southaven - Vault Guide

## Overview

This Obsidian vault contains all campaign materials for "The Heroes of Southaven," a D&D campaign. The vault is organized to support both DM planning and player reference, with clear distinctions between public information and DM-only secrets.

## Vault Structure

### Core Directories

- **`/NPCs`** - Non-player characters the party has encountered
- **`/Places`** - Locations, buildings, cities, and regions
- **`/Items`** - Magic items, special equipment, and campaign-specific gear
- **`/Organizations`** - Factions, churches, guilds, and other groups
- **`/Creatures`** - Monsters, beasts, and unique beings
- **`/Session Recaps`** - Narrative summaries of each game session
- **`/DM Notes`** - Behind-the-scenes planning, session prep, and secrets

### DM Notes Subdirectories

- **`/DM Notes/Session Notes`** - Raw bullet-point notes from each session
- **`/DM Notes/[Other Planning]`** - Campaign arcs, future plot hooks, NPC motivations, etc.

## Public vs. Private Information

### The `public` Property

Each page can have a `public` property in its frontmatter:
- `public: true` - Information known to or discoverable by players
- `public: false` - Information hidden from players (spoilers, future reveals, etc.)

### DM-Only Secrets

Use `%% %%` comment blocks within any page to hide specific information:

```md
The party knows Brenlan is Lord Kael's son.

%% 
But they don't know he's been training as a cleric while they were away.
%%
```

These blocks are invisible when the page is rendered, perfect for keeping secrets alongside public information.

## Creating New Content

Detailed instructions exist for each content type:

- **NPCs**: See [[NPC Page Template Instructions]]
- **Places**: See [[Place Page Template Instructions]]
- **Items**: See [[Item Page Template Instructions]]
- **Organizations**: See [[Organization Page Template Instructions]]
- **Creatures**: See [[Creature Page Template Instructions]]
- **Session Recaps**: See [[Session Recap Template Instructions]]

### Quick Reference Format

**NPCs**: Description → Personality → Background  
**Places**: Description → Background (optional)  
**Items**: Description → Mechanics → Notes (optional)  
**Organizations**: Description → Structure → Background  
**Creatures**: Description → Behavior → Background (optional)

## Using Wikilinks

Connect your campaign world using `[[Page Name]]` syntax:

- `[[Brenlan Kael]]` - Links to the NPC page
- `[[Brenlan Kael|Brenlan]]` - Links but displays as "Brenlan"
- `[[Session 5 - The Kidnapping of Brenlan Kael]]` - Links to session recaps

Wikilinks create a web of interconnected information, making it easy to track relationships, locations, and story threads.

## Best Practices

1. **Be consistent** - Follow the template instructions for each content type
2. **Wikilink liberally** - Connect NPCs, places, items, and sessions
3. **Hide secrets carefully** - Use `public: false` and `%% %%` blocks appropriately
4. **Write for clarity** - Keep descriptions concise (2-3 sentences per section)
5. **Update regularly** - Keep pages current as the campaign progresses
6. **Reference sessions** - Note when and where things happened
