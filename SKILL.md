---
name: shreyas-doshi-product-playbook
description: Diagnose and fix product and product-leadership problems the way Shreyas Doshi (former product leader at Stripe, Twitter, Google, Yahoo) teaches, using only his own podcasts, essays and posts, with every point cited. Use when a founder or PM has too much to do, a team that "can't execute", unclear strategy, a launch coming up, prioritization fights, misaligned execs, a hiring decision, or wants to grow as a product leader. Triggers on "LNO", "pre-mortem", "execution problem", "we're misaligned", "everything is a priority", "help me prioritize", "product strategy", "impact execution optics", "opportunity cost", "high agency", "product sense", "hire a PM", "what would Shreyas say".
---

# Shreyas Doshi's Product Leadership Playbook

An unofficial, sourced method for running a product team and a product career, built only from Shreyas
Doshi's own words: two Lenny's Podcast episodes, his Substack, and his posts on X. Who he is:
`references/00-who-is-shreyas-doshi.md`.

> "Most execution problems that I encounter in a high performing environment where everybody has the right
> intentions are actually not execution problems." [L1 00:54:49]

## Ground rules for the agent

- Every point cites `SOURCES.md` IDs: `[L1 mm:ss]`, `[L2 mm:ss]`, `[SS slug]`, `[X date]`. **Never put words
  in his mouth.** If the playbook doesn't cover it, say so.
- His frameworks are tools, not laws: "make the framework work for you, and make sure you don't work for the
  framework." [X 2023-07-19]
- Credit what he credits: LNO grew from Elizabeth Grace Saunders' INO technique; pre-mortems from Gary Klein;
  the "HELL YEAH" test from Derek Sivers; the term high agency from Eric Weinstein.

---

## Step 1: Name the situation

Ask what's going on, then route:

| The person says... | Run | Chapter / template |
|---|---|---|
| "I'm drowning / no time / too many meetings" | LNO triage | `01`, `templates/01-lno-week.md` |
| "We have a big launch / bet coming" | Pre-mortem | `02`, `templates/02-pre-mortem-kit.md` |
| "My exec and I keep disagreeing about details" | Level check | `03` |
| "The team can't execute / keeps missing" | Execution diagnosis | `04`, `templates/03-execution-diagnosis.md` |
| "We don't have a clear strategy / everything is a priority" | Strategy one-pager | `04`, `templates/04-strategy-one-pager.md` |
| "Planning / roadmap fights" | Opportunity-cost review | `05`, `templates/05-opportunity-cost-review.md` |
| "Is this feature / product any good?" | Product-sense review | `06` |
| "What should we measure?" / "Is this decision reversible?" | Metrics and decisions | `07` |
| "I need to hire a PM" | MSN list | `10`, `templates/06-msn-hiring-list.md` |
| "How do I grow as a PM / leader?" | Career review | `08`, `09`, `10` |
| Conflict, egos, influence | Listening and influence | `11`, `12` |

## Step 2: Go one level down

"The truth is one level down. Always." [SS get-to-the-core-of-the-thing] Before solving the stated problem,
check the three root causes of "execution" problems: strategy, interpersonal, culture [L1 00:54:49], and the
three levels people may be arguing from: impact, execution, optics [L1 00:46:12].

## Step 3: Deliver a session summary

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
- **At most three actions.** He is ruthless about opportunity cost.
- **Name the framework and the source** each time, so the person can read the original.
- **Push on thinking, not tools.** "Tools have never been a significant source of alpha in product success."
  [SS why-product-sense-is-the-only-product]
- **Check yourself for his named biases** (authority, analogy, alliteration, apple pie positions) before
  recommending anything. [L2 33:53 to 36:41]

A full example: `examples/01-worked-session.md`.
