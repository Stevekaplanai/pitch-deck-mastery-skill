# 🎯 Pitch Deck Mastery — Claude Skill

A Claude skill for creating investor-grade pitch decks, powered by 10 curated startup resources.

## What This Skill Does

When installed, Claude will automatically use this skill whenever you ask about pitch decks, fundraising presentations, investor slides, or deck reviews. It provides:

- **12-slide framework** adapted for pre-seed through Series B+
- **10 curated resources** (YC Library, Slidebean, Failory, etc.) with guidance on when/why to use each
- **Slide-by-slide writing guide** with templates and best practices
- **Deck review checklist** based on patterns from successful and failed decks
- **Stage-specific adjustments** so your deck matches investor expectations

## Installation

### Claude.ai (Skills)
1. Download the `.skill` file from releases (or zip this folder)
2. Go to Claude.ai → Settings → Skills
3. Upload the skill file

### Manual
Copy the `pitch-deck-mastery/` folder into your Claude skills directory.

## Skill Structure

```
pitch-deck-mastery/
├── SKILL.md                    # Main skill instructions
├── references/
│   └── resources.md            # Detailed database of all 10 resources
└── README.md                   # This file
```

## Companion Skills

This skill works best when paired with:
- **pptx** — For generating actual .pptx presentation files
- **alex-hormozi-offers** — For structuring offers and value stacks within your deck

## Resources Included

| Resource | URL | Best For |
|----------|-----|----------|
| Y Combinator Library | ycombinator.com/library | Seed-stage deck templates |
| Pitch Deck Hunt | pitchdeckhunt.com | AI/tech startup framing |
| OpenVC | openvc.app | Investor discovery + deck database |
| Alexander Jarvis | alexanderjarvis.com | Famous deck teardowns |
| Failory | failory.com/pitch-deck | Learning from failed decks |
| Deck Gallery | deck.gallery | Visual design inspiration |
| Slidebean | slidebean.com | Reconstructed iconic decks |
| Foundational | foundational.io | Early-stage founder resources |
| Startup Resources | startupresources.io | Growth & ops tool directory |
| Untapped | untapped.io | Modern funding insights |

## Example Prompts

- "Help me build a seed-stage pitch deck for my AI startup"
- "Review my pitch deck and tell me what's weak"
- "Show me how Airbnb structured their pitch deck"
- "What should my Series A deck focus on?"
- "Help me write my Problem and Solution slides"

## License

MIT
