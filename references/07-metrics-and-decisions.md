# 07 · Metrics and decisions

## Metrics are proxies for the truth

> "Ultimately, metrics are proxies for some truth." [PVP 29:35]

The truth is complicated, "So you now create proxies for that capital T truth." [PVP 29:35] His habit is to
start from what he is trying to understand about the product or business, then pick metrics by category.
[PVP 29:35]

## Six categories of product metrics

His list on X names six categories: health, usage, adoption, satisfaction, ecosystem and outcome metrics,
and asks you to consider each one when choosing metrics.
[X 2020-09-12](https://x.com/shreyas/status/1304628719374544896) On the Prime VP podcast he names five of
them and adds that there could be other categories too. [PVP 29:35]

| Category | What it tells you (his examples where we have them, otherwise **our gloss**) |
|---|---|
| **Health** | Basic health of the product: latency, uptime, errors users see [PVP 33:25] |
| **Usage** | How the feature is used and what users do with it [AMP 01:01:51] |
| **Adoption** | **Our gloss:** how many of the target users have started using it |
| **Satisfaction** | **Our gloss:** how users feel about it (ratings, surveys, support themes) |
| **Ecosystem** | **Our gloss:** effects on partners, developers, or other products around yours |
| **Outcome** | **Our gloss:** the business or user result the product exists to create |

He notes that teams often focus on impact metrics and not enough on usage metrics, while health metrics are
usually covered because engineering instruments them. [AMP 01:01:51]

## Instrument before you call it done

> "If you say you are feature-complete, but you haven't instrumented the product to be able to track basic
> usage metrics, you are not actually feature-complete." [X 2021-04-27](https://x.com/shreyas/status/1387079786107863048)

His policy in the same post: treat usage metrics like a P0 feature.

## Treat the dashboard as a product

Two things he kept seeing [AMP 01:01:51]:
1. Specs for non-trivial features often don't say what the dashboard will track. He asks for a bulleted list,
   not a mock-up.
2. Once built, "nobody is looking at that dashboard."

His fix: "why not view that as the product itself." Track the dashboard's own usage, even with “a simple
counter”, and remove friction. He pins his main metrics dashboard as a browser tab, and sends summary emails
with "some teaser high level stats, and just a link to the dashboard", because people look more closely at
metrics that get emailed. [AMP 01:01:51] He frames this as friction, not incompetence: "I think it's because
it's hard." [AMP 01:01:51]

## One to three metrics, connected to the plan

He advises giving everyone clarity on "the 1-3 metrics you are focused on, why they matter", then linking
the experiments and initiatives that will move them over the short, medium and long term.
[X 2024-01-10](https://x.com/shreyas/status/1745115821419196777)

## Honest data

> "We use data when it favors us, we use anecdotes when it favors us." [L2 21:53]

The OKR trap, in his words: "People now set OKRs so they can easily hit them."
[X 2024-06-14](https://x.com/shreyas/status/1801596278167552167) The company ends up shipping slower and
worse while hitting every OKR (same post).

Data has limits: people who insist every product decision be metrics-driven "would also have to logically
admit that theirs will be the first job to get automated by AI."
[X 2025-05-08](https://x.com/shreyas/status/1920504762812018919) On research: "By all means check out
research, but don't rely on it." [SS the-problem-with-peer-reviewed-studies]

## Decisions: most two-way doors aren't

His story from the live talk [L2 18:34 to 23:19]: a team quickly agrees to build a requested feature
because “it's a two-way door”. It takes weeks to ship. At the quarterly review adoption is low, so the team
reaches for a favourable anecdote. Sales says deals still aren't being won, someone says the feature needs to
"meet the table stakes", and the team commits to more work.

> "But now, you have signed up for even more work for a feature you should not have built in the first
> place." [L2 23:19]

> "Most doors that look like two-way doors are actually one-way doors." [L2 23:19] He adds that they are
> two-way doors at a very senior level, but for a PM leader they are one-way.

> "Sometimes it is useful to pause for two minutes, or two days, or two weeks before making that decision."
> [L2 23:19] "Thinking is cheap, so you should do more thinking, not less." [L2 25:37]

For high-stakes work: "For high-stakes situations, the outcome is paramount." [SS outcomes-learning-opportunities]

## How to apply it (our reading)

**Metrics map.** For each launch, fill one row per category (`templates/08-metrics-map.md`), then circle the
one to three you'll actually manage to. Add a view counter to the dashboard and check it after a month.

**Reversibility check** (`templates/09-decision-reversibility-check.md`). Before calling a decision
reversible, estimate what undoing it would really take:
1. Who will depend on it within a quarter (customers, sales promises, other teams)?
2. What follow-on work will “table stakes” pull in?
3. Would you actually be allowed to remove it?
**Our suggestion:** if two or more answers are “a lot”, treat it as a one-way door and use his pause.

**Worked number (invented):** a feature costs 5 engineer-weeks to build. At the QBR it needs 3 more weeks of
table stakes, then 1 week a quarter of upkeep. Over a year that's about 12 weeks, more than twice the
original estimate, for a feature with low adoption. A two-day pause to check motivation, differentiation and
distribution would have cost far less.

**Failure modes (our reading):** a dashboard nobody opens; metrics chosen because they're easy to move;
anecdotes in the review only when data is bad; calling everything a two-way door to skip thinking.

**Use it now:** `templates/08-metrics-map.md`, `templates/09-decision-reversibility-check.md`.

**Checks to run:**
1. Which of the 6 metric categories does your dashboard cover? Which is missing?
2. Is usage instrumented on everything shipped this quarter?
3. How many people opened your main dashboard last week?
4. The last decision called reversible: what would undoing it actually cost?
