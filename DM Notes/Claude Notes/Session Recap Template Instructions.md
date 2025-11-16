# Session Recap Creation Instructions

## Location
Session Recaps should be placed in the `/Session Recaps` directory of the vault.

## Process

1. **Review DM Notes** - Read the corresponding session notes in `/DM Notes/Session Notes/`
2. **Consider Campaign Context** - Think about ongoing storylines, character arcs, and plot threads
3. **Write Narrative Prose** - Transform bullet points into flowing narrative paragraphs
4. **Include Key Details** - Names, places, important decisions, and consequences

## Properties

```yaml
---
date: YYYY-MM-DD          # Real-world session date
date_solaris_start: YYYY-MM-DD  # In-game start date
date_solaris_end: YYYY-MM-DD    # In-game end date
public: true              # Usually true unless spoiler-heavy
summary: [2-4 sentence summary of the session's key events and themes]
---
```

## Structure

### Summary (Front Matter)
- **Length**: 2-4 sentences that capture the essence of the session
- **Focus**: Major decisions, dramatic moments, consequences, and themes
- **Tone**: Should build intrigue and convey the weight of events

### Body (Narrative Prose)
- **Write in paragraphs**, not bullet points
- **Use wikilinks** liberally for NPCs, places, items, and other sessions
- **Show character agency** - highlight player decisions and their reasoning
- **Build tension** - structure the narrative to maintain dramatic arc
- **Include dialogue markers** - Reference important conversations without full quotes
- **Connect scenes** - Use transitions between events
- **End with hooks** - Leave threads for future sessions

## Example Structure

**Opening**: Set the scene - where are they, what's the immediate situation?

**Middle**: Chronologically walk through major events:
- Character interactions and decisions
- Combat encounters
- Discoveries and revelations
- NPCs met and relationships developed

**Closing**: End with consequences, cliffhangers, or next steps

## Style Guidelines

1. **Active voice** - "The party broke into the courthouse" not "The courthouse was broken into"
2. **Show consequences** - Always connect actions to results
3. **Character names** - Use character names frequently, not just "the party"
4. **Wikilink first mentions** - Link NPCs and places on first reference
5. **Maintain mystery** - Don't reveal information the party doesn't know
6. **Emotional beats** - Include character feelings when relevant (fear, triumph, doubt)
7. **Pacing** - Vary paragraph length; shorter for action, longer for planning/dialogue

## Example

**File:** `/Session Recaps/Session 23 - Between Honesty and Treachery.md`

```md
---
date: 2025-09-29
date_solaris_start: 1267-07-09
date_solaris_end: 1267-07-11
public: true
summary: The party balanced on a knife's edge as the Queen demanded their aid in denying the ring's existence, destroying courthouse evidence, and assassinating Malrec. While they promised obedience, they resolved to see the truth for themselves. Crossing paths with Archdruid Thalwen Myr, who warned them to choose between honesty and treachery, only deepened the tension. That night they broke into the Balandel Courthouse, stealing two letters and uncovering both the Archdruid's plans and a secret from Judge Caelthas Sunstrider's chambers. Returning to the Queen, they learned Talan Windfern was hidden within her palace and rushed to rescue Laerwen Sylvenblade from an assassination plot, where she revealed that Lirielle—not she—was fated for the Crown of Judgement. Lirielle tested the crown and felt its power briefly before it slipped away. The night ended with blood and fire as the party infiltrated the druids' camp, assassinated Malrec, and bound themselves more tightly than ever to the Queen's perilous cause.
---

The party awoke in the [[Scarlet Shield Tavern]], where the weight of the Queen's looming trial pressed heavily on their minds. They spoke with [[Finnathan Thistle|Finn]], [[Tilly Thistle|Tilly]], and [[Velara Kael|Velara]], debating loyalties and what charges might be brought against the Queen. At the [[Queen Aelra Sylanthiel|Queen's]] estate, she revealed her intentions to the party quite plainly: the ring must be denied, the evidence in the [[Balandel Courthouse]] destroyed. Though the party outwardly agreed, they decided among themselves to examine the evidence before choosing their course.

On their way back to the inn, they crossed paths with [[Archdruid Thalwen Myr]], who demanded to know how they had visited all three distant groves in one night. She pressed them on the Verdant Reliquary and warned that they must soon choose between honesty and treachery. Uneasy but resolute, the party returned inside, where [[Momeline Sweetwater|Momeline]] pried gossip from the tavern crowd, learning that [[Talan Windfern]] had not been seen in over a week. [[Lirielle]] pulled [[Garrin Dace]] aside, who confessed that the Archdruid had questioned him about the party and that he had revealed, perhaps foolishly, that Talan was arrested by the Queensguard last week.

That night, the group broke into the [[Balandel Courthouse]]. [[Ferinthria Everflame|Ferinthria]] had to calm a frantic barking dog with her animal-speaking abilities, and Momeline slipped easily through the walls to a window from within. In the evidence chamber, they found three letters and stole two—the scrambled note from [[Lyrian Brightwind]] and a damning message from [[Serelion Thorneweave]] to [[Malrec]]—leaving the third behind. In the next room, the judge's private chamber, Momeline solved a balance puzzle to unlock a chest and read a curious note from [[Serelion Vael]], the owner of the [[Scarlet Shield Tavern]]. She chose not to take it, though. On the upper floor, they discovered the Archdruid's handwritten plans beside a sleeping Druid of the Flame. With their prizes secured, they used the Twin Orbs of Displacement to secretly return to the Queen and discuss what they had found.

The Queen revealed that the Archdruid was hunting for Talan, who was hidden in the questioning chamber in her palace, and that his discovery could be disastrous. The party informed her that the cultists planned to assassinate [[Laerwen Sylvenblade]], and they came up with a plan to send them to [[Fadrín]] with a Queensguard escort. Before sending them away, the Queen confided two more secrets: that [[Irielle Duskwhisper]] had been assigned to Saint Andral's Church, a few hours' ride from Balandel, and that [[Malrec]], whom the druids of the flame were holding captive in their camp outside the city, must not live to testify.

While helping Laerwen escape, she warned Momeline that "they think it's me, but it's your friend," hinting that Lirielle, not she, is destined to bear the [[Crown of Judgement]]. Later that night, Lirielle put on the crown herself and, unlike Momeline before her, felt a surge of agency within the vision it evoked. Just as she reached for control, the dream snapped away, leaving her shaken but certain that something greater lay within her grasp.

Slipping into the druids' camp outside the city, the party carried out the Queen's darker request. Though [[Momeline Sweetwater|Momeline]] triggered a fire rune, she and [[Lirielle]] struck quickly, assassinating [[Malrec]] before he could cry out. They fled into the night, unseen and unheard, their hands now tied more tightly than ever to the Queen's struggle to stay in power.
```

## Common Pitfalls to Avoid

1. **Don't list events** - Write flowing narrative, not bullet points
2. **Don't info-dump** - Weave in context naturally through the story
3. **Don't lose player agency** - Show character decisions, not just outcomes
4. **Don't skip emotional beats** - Include reactions, doubts, and triumphs
5. **Don't forget wikilinks** - They help readers navigate the campaign web
6. **Don't reveal DM secrets** - Only include what the party knows or discovers
7. **Don't write dry combat** - Focus on dramatic moments, not every dice roll

## Tips for Success

- Read the DM notes multiple times to internalize the flow
- Outline major beats before writing
- Write chronologically but group related events
- Use varied sentence structure for rhythm
- Include character names regularly for clarity
- End paragraphs with hooks that pull into the next scene
- Proofread for wikilink accuracy and narrative coherence
