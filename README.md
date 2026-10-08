# Shreyas Doshi's Product Leadership Playbook

**An unofficial, fully sourced playbook and AI skill for running product teams, product careers and
early-stage product decisions, built only from Shreyas Doshi's own words.**

Shreyas Doshi led products at Stripe, Twitter, Google and Yahoo, and was Stripe's first PM manager. His
frameworks (LNO, pre-mortems, impact / execution / optics, and the idea that most execution problems are really strategy problems)
are some of the most used ideas in product management. This repo turns two Lenny's Podcast episodes, an
Amplitude interview, a founder-focused podcast, 24 of his essays, 69 of his posts on X and 16 of his LinkedIn posts into a method you can
run this week, with a separate track for founders.

> "Most execution problems that I encounter in a high performing environment where everybody has the right
> intentions are actually not execution problems, they are either strategy problems or interpersonal problems
> or cultural problems." Shreyas Doshi, Lenny's Podcast (2022) [L1 00:54:49]

> ⚠️ **Unofficial.** Not written, reviewed or endorsed by Shreyas Doshi or any of the shows quoted. A
> structured guide in our own words, with short credited quotes and a link to every source.

---

## What's inside

### The playbook

| # | Chapter | What you'll learn |
|---|---|---|
| 00 | [Who Shreyas Doshi is](references/00-who-is-shreyas-doshi.md) | Background · his own warnings about his advice · mindset, principles, tactics |
| 01 | [LNO and time](references/01-lno-and-time.md) | Leverage / Neutral / Overhead · why L tasks get avoided · “no time” is something else |
| 02 | [Pre-mortems](references/02-pre-mortems.md) | The prompt · tigers, paper tigers, elephants · quiet time and the vote · the action plan |
| 03 | [Impact, execution, optics](references/03-impact-execution-optics.md) | The three levels · why you and your exec keep disagreeing · feedback by level |
| 04 | [Strategy vs execution](references/04-strategy-vs-execution.md) | The hidden root causes · “strategy” as a misused word · chief repeating officer · “be more strategic” |
| 05 | [Opportunity cost and prioritization](references/05-opportunity-cost-and-prioritization.md) | Stop maximising ROI · 60/30/10 · “HELL YEAH” |
| 06 | [Product sense](references/06-product-sense.md) | The five skills · the one-sentence test · minimum lovable product |
| 07 | [Metrics and decisions](references/07-metrics-and-decisions.md) | Metrics as proxies · six categories · dashboards as products · most two-way doors are one-way |
| 08 | [High agency](references/08-high-agency.md) | The full 2020 thread · talent times agency · how to cultivate it · what it costs |
| 09 | [Leading product teams](references/09-leading-product-teams.md) | Self-managing teams · delegation and busyness · middle management · his Stripe meetings |
| 10 | [Hiring and PM career](references/10-hiring-and-pm-career.md) | Coachable / learnable / intrinsic · MSN list · content, confidence, context |
| 11 | [Clear thinking and biases](references/11-clear-thinking-and-biases.md) | Explain by analogy, don't decide by it · biases at team level · creative intelligence |
| 12 | [Listening and influence](references/12-listening-and-influence.md) | How he learned to listen · customer conversations · blunt feedback · the Genuine Anti-Sell |
| 13 | [For founders](references/13-for-founders.md) | Problem stack rank · fired-or-promoted test · lovable vs table stakes · the CEO's strategy job · first PM hire |

Every chapter now ends with a **How to apply it** section: steps, an invented worked example, failure modes
and limits. Those sections are **our reading**, anchored to his cited ideas, and labelled as such.

### Templates

| Template | Use it to |
|---|---|
| [01 LNO week](templates/01-lno-week.md) | Label every task, find the L you're avoiding, decode “no time” |
| [02 Pre-mortem kit](templates/02-pre-mortem-kit.md) | Run a pre-mortem before a big launch |
| [03 Execution diagnosis](templates/03-execution-diagnosis.md) | Find the real cause behind “we can't execute” |
| [04 Strategy one-pager](templates/04-strategy-one-pager.md) | Write a strategy, then test whether the team actually uses it |
| [05 Opportunity-cost review](templates/05-opportunity-cost-review.md) | Re-plan a quarter by opportunity cost and the 60/30/10 guide |
| [06 MSN hiring list](templates/06-msn-hiring-list.md) | Decide what you're really hiring for, before the job description |
| [07 Product-sense review](templates/07-product-sense-review.md) | Test a product or feature against the five skills before building |
| [08 Metrics map](templates/08-metrics-map.md) | Pick metrics across his six categories, and make the dashboard get used |
| [09 Decision reversibility check](templates/09-decision-reversibility-check.md) | Find out whether a “two-way door” really is one |
| [10 Bias checklist](templates/10-bias-checklist.md) | Name the team's likely biases at kickoff and before a decision |

### Worked examples

- [A session, start to finish](examples/01-worked-session.md): a fictional 30-person startup with a stuck
  product team.
- [A founder session](examples/02-founder-session.md): a fictional six-person B2B startup whose deals stall
  after the trial.

---

## How to use this

### 1. Run it as an AI skill (10 minutes)

**Install** into your agent's skills folder. For Claude Code:

```bash
git clone https://github.com/01ayushgarg/shreyas-doshi-product-playbook \
  ~/.claude/skills/shreyas-doshi-product-playbook
```

If your agent doesn't read skill folders, paste `SKILL.md` into the chat and attach the chapters it asks for.

**Then describe what's going on.** Copy and fill in:

```text
Run a Shreyas Doshi-style session on this.

My role and company (size, stage):
Am I a founder / CEO, a PM, or a PM leader?
What's going wrong, in my words:
What we've already tried:
What's coming up in the next 2 months (launches, planning, hires):
How I spend my week right now:
```

**You get back:** the real problem one level down from the one you described, any level mismatch (impact /
execution / optics) between the people involved, at most three actions for this week with the framework and
source for each, the L task you're avoiding, and the right template to use. Every point cites the episode
timestamp, essay or post it comes from.

**Things you can ask directly:**
- *Help me LNO my week.* (paste your task list)
- *Run a pre-mortem on our launch.*
- *My team keeps missing dates. What's really going on?*
- *Is our strategy real?* (paste it)
- *Customers love the pilot but won't buy. Why?*
- *Should I hire my first PM yet?*
- *Is this decision really reversible?*
- *Why do my CEO and I keep arguing about details?*

### 2. Use the templates (no AI needed)

- Every Monday: [LNO week](templates/01-lno-week.md)
- Before any big launch: [Pre-mortem kit](templates/02-pre-mortem-kit.md) and [Metrics map](templates/08-metrics-map.md)
- Before building something new: [Product-sense review](templates/07-product-sense-review.md)
- When execution breaks: [Execution diagnosis](templates/03-execution-diagnosis.md), then [Strategy one-pager](templates/04-strategy-one-pager.md)
- Every planning cycle: [Opportunity-cost review](templates/05-opportunity-cost-review.md)
- Before a “quick” decision: [Reversibility check](templates/09-decision-reversibility-check.md)
- At a project kickoff: [Bias checklist](templates/10-bias-checklist.md)
- Every hire: [MSN list](templates/06-msn-hiring-list.md)

### 3. Read it

| If your problem is... | Read |
|---|---|
| I'm a founder and nothing is landing | 13, then 06 and 04 |
| I'm drowning | 01, 05, 09 |
| We have a big launch coming | 02, 07 |
| My exec and I keep clashing | 03, 12 |
| The team can't execute | 04 |
| Is this product any good? | 06 |
| What should we measure? | 07 |
| How do I become a better product leader? | 08, 09, 10 |
| Am I thinking clearly about this? | 11 |

**His own caveat:** "make the framework work for you, and make sure you don't work for the framework." [X 2023-07-19](https://x.com/shreyas/status/1681697116027068418)

---

## How it stays honest

- **First-party only:** his podcasts and interviews, his essays, his posts. No summaries by other people.
  For podcasts and interviews, only his own turns are quoted, never the host's.
- **How quotes were checked:** before publishing, a script compared every quoted string against our saved
  copies of the sources, and against the specific source ID each quote cites. That script needs those
  private copies, so it isn't shipped. Every quote links to a public source, so you can check it yourself.
- **Short quotes:** no quote is over about 60 words, trims are marked with “...”, and list-style posts are
  paraphrased rather than copied.
- **Our reading is labelled:** steps, thresholds, worked numbers and glosses that are ours are marked
  **Our reading** or **Our suggestion**.
- **AI-written text excluded:** lines from AI chats published on his Substack, and its AI-generated audio
  posts, are not used.
- **Credit where he gives it:** Saunders (INO), Sivers (“HELL YEAH”), Weinstein (the term high agency),
  Kahneman (the Focusing Illusion). He says minimum lovable product isn't his idea either.
- **His updates are shown:** where his view changed (on high agency), both versions are included with dates.

## Sources

Lenny's Podcast (2022 and 2024), Amplitude's *Product Lessons Learned* interview (2021), the Prime Venture
Partners podcast (2021), 24 posts from his Substack (2025 to 2026), 69 posts on X (2020 to 2026, including the
full 2020 high-agency thread), 16 posts on LinkedIn (July to October 2026), and his Maven bio. Full list with links and dates in [`SOURCES.md`](SOURCES.md).

## License

- **Our text** (chapters, skill, templates, structure): [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- **Quotes** remain Shreyas Doshi's words (and his hosts'). Short, credited excerpts for commentary, **not**
  covered by this license.

See [`LICENSE`](LICENSE).

## Corrections

Spot a misquote or a broken link? Open an issue with the source link.
