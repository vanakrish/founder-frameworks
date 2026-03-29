# Founder Frameworks

Think through any leadership challenge using the mental models of 9 legendary founders — as a [Claude Code](https://docs.anthropic.com/en/docs/claude-code) plugin.

22 interactive skills distilled from [David Senra's Founders Podcast](https://www.founderspodcast.com/), turning founder philosophies into actionable decision tools you can invoke from your terminal.

## The 9 Founders

| Founder | Company | Core Philosophy |
|---------|---------|-----------------|
| **Steve Jobs** | Apple | Design for how things ought to be |
| **Elon Musk** | Tesla, SpaceX | Maniacal sense of urgency + first principles |
| **Bill Gates** | Microsoft | Fanatical focus and relentless competitiveness |
| **Jeff Bezos** | Amazon | Long-term thinking and infrastructure |
| **Jensen Huang** | NVIDIA | Complacency kills — paranoia as a virtue |
| **Larry Ellison** | Oracle | Contrarian conviction — burn the boats |
| **Michael Dell** | Dell | Capital efficiency and direct customer relationships |
| **James Dyson** | Dyson | Stubbornness over vision — 5,127 prototypes |
| **Dietrich Mateschitz** | Red Bull | The money flows as a function of the stories |

## Install

Requires [Claude Code](https://docs.anthropic.com/en/docs/claude-code) (Anthropic's CLI for Claude).

**Step 1** — Add this repo as a marketplace:

```
/plugin marketplace add vanakrish/founder-frameworks
```

**Step 2** — Install the plugin:

```
/plugin install fnd@vanakrish-founder-frameworks
```

That's it. All 22 skills are now available as `/fnd:*` commands in any project.

### Verify Installation

```
/fnd:navigate
```

This will route you to the right skill based on your challenge.

## Usage

### Option A: Not sure where to start?

```
/fnd:navigate
```

The navigator asks about your challenge and recommends the best skill(s).

### Option B: Pick a founder lens

Apply one founder's complete philosophy to your problem:

```
/fnd:lens-jobs I have 12 product SKUs and none are winning. What should I do?
```

```
/fnd:lens-bezos Our SaaS is growing 20% but we're burning cash and the board wants profitability
```

```
/fnd:lens-musk We need to cut our production cost by 40% or we're dead
```

### Option C: Pick a topic

Get cross-founder wisdom on a specific decision context:

```
/fnd:think-hiring I need to hire my first VP of Engineering
```

```
/fnd:think-competition A well-funded competitor just entered our market
```

```
/fnd:think-focus I have 6 initiatives running and none are getting enough attention
```

## All 22 Skills

### Founder Lens Skills — Think through ANY problem as a specific founder

| Skill | Founder | Best for |
|-------|---------|----------|
| `/fnd:lens-jobs` | Steve Jobs | Vision, design, intuition, saying no |
| `/fnd:lens-musk` | Elon Musk | First principles, speed, manufacturing, urgency |
| `/fnd:lens-gates` | Bill Gates | Fanatical focus, competitive analysis, conflict |
| `/fnd:lens-bezos` | Jeff Bezos | Long-term thinking, curiosity, infrastructure |
| `/fnd:lens-jensen` | Jensen Huang | Paranoia, teaching, market creation, craft |
| `/fnd:lens-ellison` | Larry Ellison | Contrarian conviction, narrative, simplicity |
| `/fnd:lens-dell` | Michael Dell | Direct model, capital efficiency, customer intimacy |
| `/fnd:lens-dyson` | James Dyson | Stubbornness, iteration, craftsmanship, pain |
| `/fnd:lens-redbull` | Dietrich Mateschitz | Storytelling, category creation, media-as-marketing |

### Topic Skills — Cross-founder wisdom by decision context

| Skill | What it does | Draws from |
|-------|-------------|-----------|
| `/fnd:think-product` | Product quality, design, and innovation | Jobs, Dyson, Musk, Bezos |
| `/fnd:think-hiring` | Hiring, team building, and org structure | Jobs, Gates, Jensen, Dell, Dyson |
| `/fnd:think-decisions` | High-stakes decisions under uncertainty | Bezos, Musk, Ellison, Gates |
| `/fnd:think-competition` | Competitive strategy and positioning | Gates, Ellison, Jensen, Mateschitz |
| `/fnd:think-focus` | Prioritization and saying no | Jobs, Gates, Jensen, Musk |
| `/fnd:think-innovation` | R&D, prototyping, and iteration | Dyson, Musk, Bezos, Dell |
| `/fnd:think-storytelling` | Brand narrative and content-as-marketing | Mateschitz, Jobs, Ellison |
| `/fnd:think-scaling` | Growing without losing culture | Jensen, Gates, Dell, Bezos |
| `/fnd:think-resilience` | Pushing through failure and setbacks | Dyson, Musk, Jobs, Dell |
| `/fnd:think-customer` | Getting closer to customers | Dell, Bezos, Dyson, Jobs |
| `/fnd:think-contrarian` | Going against consensus | Ellison, Bezos, Mateschitz, Dyson |
| `/fnd:think-capital` | Financial strategy and capital efficiency | Dell, Gates, Mateschitz, Bezos |

### Navigator

| Skill | What it does |
|-------|-------------|
| `/fnd:navigate` | Routes you to the right skill based on your challenge |

## Not sure which founder? Match your vibe

| Your vibe | Try this |
|-----------|---------|
| "I need to simplify and focus" | `/fnd:lens-jobs` |
| "I need to move faster" | `/fnd:lens-musk` |
| "I need to outcompete someone" | `/fnd:lens-gates` |
| "I need to think longer-term" | `/fnd:lens-bezos` |
| "I need to push my team harder" | `/fnd:lens-jensen` |
| "I want to go against the grain" | `/fnd:lens-ellison` |
| "I need capital efficiency" | `/fnd:lens-dell` |
| "I need to persevere through setbacks" | `/fnd:lens-dyson` |
| "I need to build a brand/story" | `/fnd:lens-redbull` |

## How it works

Each skill encodes a founder's actual mental models, decision-making patterns, and philosophies from the Founders Podcast. When you invoke one:

1. **Describe your situation** — Pass your challenge as an argument
2. **The skill processes it** — Through that founder's specific thinking patterns and mental models
3. **You get an opinionated recommendation** — In their voice, with actual quotes
4. **Plus**: Their blind spots, what they'd sacrifice, and a **post-worthy takeaway** you can share

The topic skills (`think-*`) pull from multiple founders on the same challenge, highlighting where they **agree** and where they **clash** — because the tensions between founders is where the real decisions live.

## Credit

All principles, quotes, and philosophies are sourced from **[David Senra's Founders Podcast](https://www.founderspodcast.com/)** — episodes covering biographies and interviews of these 9 founders. The podcast is the source material; these skills make it actionable.

## License

MIT
