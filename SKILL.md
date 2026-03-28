---
name: pitch-deck-mastery
description: "Complete framework for creating investor-grade pitch decks using 10 curated startup resources and proven deck structures. Use this skill whenever the user mentions pitch decks, investor presentations, fundraising decks, startup pitches, demo day slides, deck reviews, or wants feedback on an existing pitch deck. Also trigger when users reference Y Combinator decks, want to study successful pitch decks, need help with fundraising narratives, or ask about deck structure for any startup stage (pre-seed, seed, Series A, Series B+). Even if the user just says 'deck' or 'slides' in a startup/fundraising context, use this skill."
---

# Pitch Deck Mastery

Create investor-grade pitch decks informed by patterns from the world's best startup decks.

> **Companion skills:** Use the `pptx` skill for actual .pptx file creation. Use `alex-hormozi-offers` if structuring a product/service offer within the deck.

---

## The Standard Pitch Deck Structure

Every great deck follows a narrative arc. Here is the proven 12-slide framework used by top-funded startups:

| # | Slide | Purpose | Key Question It Answers |
|---|-------|---------|------------------------|
| 1 | Title | First impression, brand, one-liner | "What is this company?" |
| 2 | Problem | Pain point with evidence | "Why does this matter?" |
| 3 | Solution | Your product/approach | "How do you solve it?" |
| 4 | Why Now | Market timing & tailwinds | "Why is now the right time?" |
| 5 | Market Size | TAM → SAM → SOM | "How big is the opportunity?" |
| 6 | Product | Demo, screenshots, how it works | "What does it look like?" |
| 7 | Traction | Metrics, growth, milestones | "Is it working?" |
| 8 | Business Model | Revenue, pricing, unit economics | "How do you make money?" |
| 9 | Competition | Positioning map or matrix | "Why will you win?" |
| 10 | Team | Founders + key hires, why them | "Can you execute?" |
| 11 | Financials | Projections, use of funds | "What do you need & where does it go?" |
| 12 | Ask | Raise amount, terms, next steps | "What are you asking for?" |

### Stage-Specific Adjustments

| Stage | Slides to Emphasize | Slides to Minimize | Deck Length |
|-------|---------------------|--------------------|-------------|
| Pre-seed | Problem, Solution, Team, Why Now | Financials, Competition | 8-10 slides |
| Seed | Traction, Product, Market Size | Detailed financials | 10-12 slides |
| Series A | Traction, Unit Economics, Go-to-Market | Problem (brief) | 12-15 slides |
| Series B+ | Metrics, Financials, Expansion Plan | Problem, Solution (brief) | 15-20 slides |

---

## Deck Design Principles

Patterns extracted from the highest-performing decks across all major resources:

### Content Rules
1. **One idea per slide** — If you need a second point, make a second slide
2. **Lead with the headline** — Each slide title should be the takeaway, not a label (e.g., "Revenue grew 3x in 6 months" not "Revenue")
3. **Show, don't tell** — Screenshots, charts, and demos over bullet points
4. **Quantify everything** — Replace adjectives with numbers ("large market" → "$47B market")
5. **10-word rule** — No bullet point should exceed 10 words

### Visual Rules
1. **Max 3 fonts** — One for headings, one for body, one for accents
2. **Consistent color palette** — 2-3 brand colors + 1 accent for emphasis
3. **White space is your friend** — Crowded slides signal unclear thinking
4. **Left-to-right, top-to-bottom** — Respect natural reading flow
5. **Charts over tables** — Unless precision matters more than trend

### Narrative Rules
1. **Problem → Solution arc** — Make the investor feel the pain before revealing the cure
2. **Credibility stacking** — Each slide should build on the last
3. **End with momentum** — Your Ask slide should feel like an inevitability, not a request
4. **The "So What?" test** — Every slide must pass: "Why should the investor care about this?"

---

## Deck Review Checklist

When reviewing an existing deck, evaluate against these criteria:

### Must-Pass (Instant Rejection if Missing)
- [ ] Clear one-liner on title slide
- [ ] Specific, quantified problem
- [ ] Solution clearly tied to the problem
- [ ] Market size with credible sourcing
- [ ] Team slide with relevant credentials
- [ ] Clear ask (amount + use of funds)

### Strength Signals (What Makes Decks Stand Out)
- [ ] Traction chart showing growth trajectory
- [ ] Named customers or logos
- [ ] Unit economics demonstrated
- [ ] Competitive positioning that's honest, not dismissive
- [ ] "Why Now" slide with a genuine insight
- [ ] Consistent visual identity throughout

### Common Mistakes (From Failory's Failed Deck Analysis)
- [ ] No wall-of-text slides
- [ ] No unsourced market size claims
- [ ] No "we have no competition" positioning
- [ ] No vanity metrics without context
- [ ] No more than 15 slides for seed stage
- [ ] No generic team bios (show domain expertise)

---

## Using the Research Resources

Claude has access to 10 curated pitch deck resources. Read `references/resources.md` for the full database with URLs, use cases, and what to look for in each.

### Quick Reference: When to Use Which Resource

| Need | Best Resource | Why |
|------|---------------|-----|
| Seed-stage deck template | Y Combinator Library | Gold standard for early-stage clarity |
| AI/tech startup framing | Pitch Deck Hunt | Curated AI deck collection |
| Find investors by stage | OpenVC | Searchable investor + deck database |
| Study famous decks in depth | Alexander Jarvis | Professional-grade deck teardowns |
| Learn from failures | Failory | Failed deck analysis to avoid mistakes |
| Visual storytelling inspiration | Deck Gallery | Best-designed deck archive |
| Reconstructed iconic decks | Slidebean | Airbnb, Uber, Buffer deck rebuilds |
| Early-stage founder resources | Foundational | Broad founder toolkit |
| Growth & ops tools | Startup Resources | Curated startup tool directory |
| Modern funding insights | Untapped | How startups get built and funded today |

### How to Research for a User

When a user asks Claude to help with a pitch deck, Claude should:

1. **Identify the stage** — Pre-seed, seed, Series A, or later
2. **Fetch relevant examples** — Use `web_fetch` to pull examples from the appropriate resource (see `references/resources.md` for URLs)
3. **Apply the framework** — Use the 12-slide structure above, adjusted for stage
4. **Review against checklist** — Run through the Must-Pass and Strength Signals
5. **Reference real decks** — Point users to specific examples from the resources that match their industry/stage

---

## Slide-by-Slide Writing Guide

### Slide 1: Title
```
[Company Name]
[One-liner: What you do in ≤10 words]
[Stage] | [Raising $X]
[Contact info]
```
**Tips:** The one-liner should pass the "mom test" — would a non-technical person understand it? Avoid jargon.

### Slide 2: Problem
- State the problem in human terms first, then quantify
- Use a real quote or scenario if possible
- Show the cost of the status quo (time, money, frustration)
- Frame: "X people face Y problem, costing them Z"

### Slide 3: Solution
- Lead with the outcome, not the feature
- One screenshot or visual of the product
- Max 3 key differentiators
- Frame: "We do X so that Y can Z"

### Slide 4: Why Now
Best "Why Now" triggers:
- Regulatory change
- Technology inflection (AI, mobile, cloud)
- Behavior shift (remote work, creator economy)
- Market failure (incumbent stagnation)
- Cost curve crossing (something just became cheap enough)

### Slide 5: Market Size
```
TAM: Total addressable market (the whole universe)
SAM: Serviceable addressable market (who you could reach)
SOM: Serviceable obtainable market (realistic year 1-3 target)
```
**Rules:** Bottom-up > top-down. "The market is $X billion" is weak. "There are X customers who pay $Y/year for Z, giving us a SAM of $X" is strong.

### Slide 6: Product
- Show the product in action (screenshots, demo flow, architecture)
- Highlight the "aha moment" — what makes users stay
- Keep it visual, minimal text
- If pre-product, show mockups or prototypes

### Slide 7: Traction
Best metrics by stage:

| Stage | Primary Metrics |
|-------|----------------|
| Pre-seed | Waitlist, LOIs, pilot commitments |
| Seed | MRR, user growth rate, retention |
| Series A | Revenue, NDR, CAC/LTV, growth rate |

**Always show trajectory**, not just a snapshot. A chart going up-and-to-the-right is the most powerful slide in any deck.

### Slide 8: Business Model
- Show how money flows: Customer → You → Value delivery
- Include key unit economics if available (CAC, LTV, margins)
- Pricing model clarity: subscription, usage-based, marketplace take rate
- Show expansion potential (upsell, cross-sell, platform)

### Slide 9: Competition
**Use a 2x2 matrix** (not a feature checklist where you win everything — investors see through this). Pick two dimensions that matter most to customers and position yourself in the best quadrant.

### Slide 10: Team
- Name, photo, title, one credential line per person
- Highlight domain expertise and "why this team wins"
- Notable advisors or investors (logos if possible)
- Don't list every team member — focus on founders + key hires

### Slide 11: Financials
- 3-year projection (keep it simple)
- Key assumptions clearly stated
- Use of funds breakdown (pie chart or bar)
- Path to profitability or next milestone

### Slide 12: Ask
- Amount raising and instrument (SAFE, priced round, etc.)
- What milestones the raise enables
- Timeline for deployment
- Contact information and next steps

---

## Quick-Start Templates

### For Pre-Seed (8 slides)
Title → Problem → Solution → Why Now → Product → Team → Market → Ask

### For Seed (12 slides)
Full 12-slide framework as described above

### For Series A (15 slides)
Full 12 slides + Go-to-Market + Case Studies + Expansion Plan

---

## Integration Notes

- **To create the actual .pptx file:** Use the `pptx` skill after structuring content with this skill
- **To structure an offer within the deck:** Reference the `alex-hormozi-offers` skill for value stacking and pricing
- **To research competitors or market data:** Use `web_search` and `web_fetch` tools
- **To fetch example decks:** Use URLs from `references/resources.md` with `web_fetch`
