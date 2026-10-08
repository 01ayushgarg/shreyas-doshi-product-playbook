---
name: shreyas-doshi-product-playbook
description: Diagnose and fix product, product-leadership and early-stage founder problems the way Shreyas Doshi (former product leader at Stripe, Twitter, Google, Yahoo) teaches, using only his own podcasts, interviews, essays and posts, with every point cited. Use when a founder or PM has too much to do, a team that can't execute, unclear strategy, a launch coming up, prioritization fights, misaligned execs, pilots that don't convert, a first PM hire or any hiring decision, metrics questions, a “reversible” decision, or wants to grow as a product leader. Triggers on LNO, pre-mortem, execution problem, we're misaligned, everything is a priority, help me prioritize, product strategy, impact execution optics, opportunity cost, high agency, product sense, minimum lovable product, two-way door, first PM hire, what would Shreyas say.
---

# Shreyas Doshi's Product Leadership Playbook

An unofficial, sourced method for running a product team, a product career and early-stage product
decisions, built only from Shreyas Doshi's own words: two Lenny's Podcast episodes, an Amplitude interview,
a Prime Venture Partners podcast, his Substack, and his posts on X and LinkedIn. Who he is:
`references/00-who-is-shreyas-doshi.md`.

> "Most execution problems that I encounter in a high performing environment where everybody has the right
> intentions are actually not execution problems." [L1 00:54:49]

## Ground rules for the agent

- Every point cites `SOURCES.md` IDs: `[L1 hh:mm:ss]`, `[L2 mm:ss]`, `[AMP hh:mm:ss]`, `[PVP mm:ss]`,
  `[SS slug]`, `[X yyyy-mm-dd]`, `[LI yyyy-mm-dd](url)`. **Never put words in his mouth.** If the playbook doesn't cover it, say so.
- LinkedIn posts: always cite with the link, because two posts can share a date. Many of them only introduce
  one of his videos; cite what the post says, and never claim to know what the video says.
- Keep his words and ours apart. The “How to apply it” sections, numbers, thresholds and template steps
  marked **Our reading** / **Our suggestion** are not his; say so when you use them.
- His frameworks are tools, not laws: "make the framework work for you, and make sure you don't work for the
  framework." [X 2023-07-19] He also says context matters most and not to implement his advice just because
  you like it. [PVP 02:45] [AMP 00:01:07]
- Credit what he credits, and nothing more: LNO grew from Elizabeth Grace Saunders' INO technique; the
  “HELL YEAH” test is Derek Sivers'; the term high agency is Eric Weinstein's; the Focusing Illusion is
  Kahneman's; minimum lovable product is, in his words, not his idea. Our sources don't name who invented
  the pre-mortem, so don't credit anyone.
- Some things are named but not explained in the sources (for example the Radical Delegation Framework, and
  the image-only detail of product vs project thinking). Say that rather than filling the gap.

---

## Step 1: Who is asking?

- **Founder or CEO of an early-stage company** (roughly pre-product-market-fit, or under about 50 people,
  our suggestion): start with `references/13-for-founders.md` and the founder routes below.
- **PM or PM leader:** use the main routes.

## Step 2: Name the situation and route

| The person says... | Run | Chapter / template |
|---|---|---|
| Customers like the pilot but won't buy / “talk next quarter” | Problem stack rank, fired-or-promoted test | `13`, `templates/07-product-sense-review.md` |
| A big prospect wants a list of table stakes | Lovable vs below par, narrow segment, reversibility check | `13`, `06`, `templates/09-decision-reversibility-check.md` |
| Everything escalates to me (founder) | Strategy one-pager, chief repeating officer | `13`, `04`, `templates/04-strategy-one-pager.md` |
| Should I hire my first PM? | MSN list, coachable / intrinsic, what to hand over | `13`, `10`, `templates/06-msn-hiring-list.md` |
| I'm drowning / no time / too many meetings | LNO triage, delegation audit | `01`, `09`, `templates/01-lno-week.md` |
| We have a big launch / bet coming | Pre-mortem, metrics map | `02`, `07`, `templates/02-pre-mortem-kit.md`, `templates/08-metrics-map.md` |
| My exec and I keep disagreeing about details | Level check | `03` |
| The team can't execute / keeps missing | Execution diagnosis | `04`, `templates/03-execution-diagnosis.md` |
| We don't have a clear strategy / everything is a priority | Strategy one-pager | `04`, `templates/04-strategy-one-pager.md` |
| I was told to be more strategic | The three types of that feedback | `04`, `10` |
| Planning / roadmap fights | Opportunity-cost review | `05`, `templates/05-opportunity-cost-review.md` |
| Is this feature / product any good? | Product-sense review | `06`, `templates/07-product-sense-review.md` |
| What should we measure? | Metrics map | `07`, `templates/08-metrics-map.md` |
| Is this decision reversible? / “It's a two-way door” | Reversibility check | `07`, `templates/09-decision-reversibility-check.md` |
| I need to hire a PM | MSN list | `10`, `templates/06-msn-hiring-list.md` |
| How do I grow as a PM / leader? | Career review | `08`, `09`, `10` |
| Are we thinking clearly? / big decision coming | Bias checklist | `11`, `templates/10-bias-checklist.md` |
| Conflict, egos, influence, feedback | Listening and influence | `12` |

## Step 3: Go one level down

"The truth is one level down. Always." [SS get-to-the-core-of-the-thing] Before solving the stated problem,
check the root causes of “execution” problems: strategy, interpersonal, culture [L1 00:54:49], and the three
levels people may be arguing from: impact, execution, optics [L1 00:46:12]. For founders, also check whether
the problem solved is "in the stack rank of priorities" for the customer [PVP 02:45].

## Step 4: Deliver a session summary

```markdown
# Session: [person / team]

**The real problem:** [one sentence, one level down from the stated one]
**Level mismatch?** [impact / execution / optics, who's where]

## Do this week
1. [Specific action] · framework · [source]
2. ...

## The L task you're avoiding
- [task] · the fear behind it · first step

## Questions to sit with
- "Is this the very best use of my time & energy?" [SS sometimes-you-should-talk-to-fewer]
- ...
```

Rules:
- **At most three actions** (our suggestion, in the spirit of his opportunity-cost thinking).
- **Name the framework and the source** each time, so the person can read the original.
- **Push on thinking, not tools.** "Tools have never been a significant source of alpha in product success."
  [SS why-product-sense-is-the-only-product]
- **Check yourself for his named biases** (authority, alliteration, analogy, apple pie positions,
  confirmation, fundamental attribution) before recommending anything. [L2 33:53 to 36:41] [AMP 00:54:37]

Full examples: `examples/01-worked-session.md` (PM leader) and `examples/02-founder-session.md` (founder).
