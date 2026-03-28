# Pitch Deck Resources Database

10 curated resources for studying, building, and refining startup pitch decks. Use `web_fetch` to pull examples from these sources when helping users.

---

## Resource Directory

### 1. Y Combinator Library
| Field | Detail |
|-------|--------|
| **URL** | https://www.ycombinator.com/library |
| **Best For** | Seed-stage deck templates, founder advice, clarity-first approach |
| **What to Look For** | YC emphasizes extreme clarity and brevity. Their decks strip away fluff and focus on problem-solution-traction. Study how YC companies communicate complex tech in simple terms. |
| **Stage** | Pre-seed, Seed |
| **Key Insight** | YC decks rarely exceed 10 slides. Every word earns its place. If YC-backed founders can explain quantum computing in 8 slides, your SaaS can too. |

### 2. Pitch Deck Hunt
| Field | Detail |
|-------|--------|
| **URL** | https://www.pitchdeckhunt.com |
| **Best For** | AI company pitch decks, tech startup framing, modern deck trends |
| **What to Look For** | Curated collection focused on how AI and tech companies position their technology for non-technical investors. Great for studying how to explain technical products. |
| **Stage** | All stages |
| **Key Insight** | AI companies that raise well don't lead with the technology — they lead with the problem and use AI as the "why now" and "why us" answer. |

### 3. OpenVC
| Field | Detail |
|-------|--------|
| **URL** | https://www.openvc.app |
| **Best For** | Searchable deck database, investor discovery, fundraising research |
| **What to Look For** | Search by industry, stage, and raise amount. Also useful for finding investors who fund specific verticals. Use the deck examples to benchmark against peers. |
| **Stage** | All stages |
| **Key Insight** | OpenVC decks show what real (not reconstructed) decks look like — imperfections and all. This is useful for setting realistic quality expectations. |

### 4. Alexander Jarvis
| Field | Detail |
|-------|--------|
| **URL** | https://www.alexanderjarvis.com/pitch-deck-collection/ |
| **Best For** | Deep analysis of famous decks (Airbnb, LinkedIn, Sequoia, etc.) |
| **What to Look For** | Professional-grade teardowns with commentary on what worked, what didn't, and why. Jarvis provides historical context on how decks evolved through funding rounds. |
| **Stage** | All stages (historical analysis) |
| **Key Insight** | The best decks evolve dramatically between rounds. Studying the same company's seed vs. Series A deck reveals how narrative shifts as traction grows. |

### 5. Failory
| Field | Detail |
|-------|--------|
| **URL** | https://www.failory.com/pitch-deck |
| **Best For** | Learning from failed decks, avoiding common mistakes, pattern recognition |
| **What to Look For** | Both successful AND failed decks with analysis. The failed decks are uniquely valuable — they show what NOT to do (vague markets, missing traction, weak teams). |
| **Stage** | All stages |
| **Key Insight** | The #1 pattern in failed decks: vague problem statements. If the problem slide doesn't make the investor uncomfortable, it's not specific enough. |

### 6. Deck Gallery
| Field | Detail |
|-------|--------|
| **URL** | https://www.deck.gallery |
| **Best For** | Visual design inspiration, storytelling through design, beautiful deck layouts |
| **What to Look For** | Focus on how decks use whitespace, typography, color, and layout to enhance (not distract from) the narrative. This is the resource for design quality. |
| **Stage** | All stages |
| **Key Insight** | The best-designed decks use visual hierarchy to guide the eye. Title → key metric → supporting detail. Never make the investor hunt for the point. |

### 7. Slidebean
| Field | Detail |
|-------|--------|
| **URL** | https://slidebean.com/pitch-deck-examples |
| **Best For** | Reconstructed iconic decks (Airbnb, Uber, Buffer, etc.), side-by-side analysis |
| **What to Look For** | Slidebean rebuilds famous decks with modern design and provides video breakdowns. Great for understanding the structure behind legendary pitches. |
| **Stage** | Seed, Series A |
| **Key Insight** | Airbnb's original deck was 10 slides. Buffer's was 13. The best decks are shorter than you think. Slidebean's reconstructions show you can be comprehensive AND concise. |

### 8. Foundational
| Field | Detail |
|-------|--------|
| **URL** | https://foundational.io |
| **Best For** | Early-stage founder resources, startup building blocks, fundraising preparation |
| **What to Look For** | Broader than just decks — covers the full early-stage journey. Use for context on what investors expect at different stages and how to prepare before deck creation. |
| **Stage** | Pre-seed, Seed |
| **Key Insight** | The deck is the last thing you should build. Foundational emphasizes getting the fundamentals right (problem validation, customer discovery, business model) before touching slides. |

### 9. Startup Resources
| Field | Detail |
|-------|--------|
| **URL** | https://startupresources.io |
| **Best For** | Curated tools for growth, operations, and deck creation tooling |
| **What to Look For** | Directory of tools organized by category. Useful for recommending specific tools for deck design, financial modeling, market research, and pitch practice. |
| **Stage** | All stages |
| **Key Insight** | The best decks are backed by real tools — financial models from proper spreadsheets, market data from research tools, and designs from professional software. |

### 10. Untapped
| Field | Detail |
|-------|--------|
| **URL** | https://www.untapped.io |
| **Best For** | Modern startup funding insights, how today's startups get built and funded |
| **What to Look For** | Insights into current fundraising trends, what investors are looking for right now, and how the startup ecosystem is evolving. Good for staying current. |
| **Stage** | All stages |
| **Key Insight** | Fundraising norms change fast. What worked in 2021 (growth at all costs) is different from 2024+ (efficiency, path to profitability). Untapped tracks these shifts. |

---

## Resource Selection Guide

### By Task

| Task | Primary Resource | Secondary Resource |
|------|-----------------|-------------------|
| Writing a seed deck from scratch | Y Combinator Library | Slidebean |
| Reviewing/improving an existing deck | Failory | Alexander Jarvis |
| Design and visual polish | Deck Gallery | Slidebean |
| AI/tech company positioning | Pitch Deck Hunt | OpenVC |
| Studying famous decks | Alexander Jarvis | Slidebean |
| Finding investor fit | OpenVC | Untapped |
| Pre-deck preparation | Foundational | Startup Resources |
| Market research for deck | Startup Resources | OpenVC |
| Understanding current trends | Untapped | Pitch Deck Hunt |
| Avoiding common mistakes | Failory | Y Combinator Library |

### By Industry

| Industry | Best Resources |
|----------|---------------|
| AI/ML | Pitch Deck Hunt, OpenVC |
| SaaS | Slidebean, Alexander Jarvis |
| Fintech | OpenVC, Alexander Jarvis |
| Consumer | Deck Gallery, Slidebean |
| Hardware | Y Combinator Library, Foundational |
| Marketplace | Slidebean (Airbnb/Uber examples), OpenVC |
| Healthcare | OpenVC, Startup Resources |

---

## Fetching Examples

When helping a user, use `web_fetch` to pull relevant content:

```
# Example: Fetch YC library content
web_fetch("https://www.ycombinator.com/library")

# Example: Fetch Slidebean examples
web_fetch("https://slidebean.com/pitch-deck-examples")

# Example: Fetch OpenVC decks
web_fetch("https://www.openvc.app")
```

**Important:** These are live URLs. Content may change. Always verify what you fetch is current and relevant before presenting to the user.
