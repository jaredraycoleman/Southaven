# NPC Page Creation Instructions

## Location
NPCs should be placed in the `/NPCs` directory of the vault.

## Properties
- If the entire NPC should not be known yet to the players, set the `public` flag in the properties to `false`
- Information that should be hidden from players and only visible to the DM should be in `%% %%` comment blocks

## Markdown Format

```md
## Description
[2-3 sentence physical description of the NPC]

## Personality
[2-3 sentences on the NPC's personality]

## Background
[background of character before or during campaign]
```

## Example

**File:** `/NPCs/Brenlan Kael.md`

```md
---
public: true
---

## Description

Brenlan Kael is a young man of approximately 23 years, possessing an unassuming charm. With tousled blonde hair that catches the light in vibrant shades of gold, his gentle blue eyes radiate curiosity and warmth. He has a lean build, typical of someone who spends more time in libraries and courts than in training grounds. His attire, often neat but slightly disheveled, consists of well-tailored tunics in shades of blue and green, reminiscent of his noble lineage.

He bears the insignia of House Kael—a stylized silver eagle—embroidered subtly on his clothing, but he prefers a more humble approach in his day-to-day interactions outside the court.

## Personality

Brenlan is kind-hearted and introspective, occasionally overshadowed by the expectations that come with his noble birth. He often comes off as timid, especially when engaging with those who seem more adventurous or confident. Yet, beneath this exterior lies a spirited dreamer, one who is deeply fascinated by tales of heroism, magic, and the unknown.

He is a good listener and has a knack for asking insightful questions, often leading others to share their stories about distant lands and epic battles. Brenlan tends to avoid confrontations and prefers to resolve conflicts peacefully, often seeking the advice of others before acting himself.

## Background

As the son of Lord Kael of Southaven, Brenlan enjoys a privileged life with access to education and resources. However, he often feels the weight of his family's legacy pressing down upon him. Raised in the lavish halls of Southaven's castle, he was expected to follow in his father's footsteps and take on responsibilities that come with nobility.

Despite this, Brenlan yearns for adventure and is often found hidden in the castle's library, captivated by tales of heroes and legends. His days are filled with study and dreams of the great world outside, where he imagines himself as part of the stories he so loves to read. He frequently dreams of joining adventurers on grand quests, but self-doubt often holds him back from taking bold steps toward that freedom.

The party met Brenlan in [[Session 3 - The Hag of Blacktide Swamp]] after defeating the hag. [[Momeline Sweetwater|Momeline]] gifted him a crocodile's tooth and he was very interested in their adventures. He became friendly with them and saw the party at [[Rusty's Tavern]] often. In [[Session 5 - The Kidnapping of Brenlan Kael]], Brenlan was kidnapped by [[Donavar Reddmark]] and the party saved him.

%% 
While the party has been gone in [[Lusteris]] and [[Balandel]], he has been training as a cleric in the [[The Church of Elandria]]. 
%%
```

## Key Points

1. **Keep descriptions concise** - 2-3 sentences per section
2. **Use wikilinks** - Link to other relevant pages using `[[Page Name]]` or `[[Page Name|Display Name]]`
3. **DM-only info** - Use `%% %%` comment blocks for secrets
4. **Physical first** - Description focuses on appearance
5. **Personality second** - How they act and think
6. **Background last** - Their history and campaign involvement
7. **Include campaign connections** - Reference sessions and other NPCs where relevant
