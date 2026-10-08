# Template 08 · Metrics map

For every non-trivial launch, written into the spec. Based on `references/07-metrics-and-decisions.md`. The six
categories are his [X 2020-09-12]; the layout, the column prompts and the review cadence are our suggestion.

Product / feature: ______________________  Owner (he says the PM, or whoever plays that role, owns it
[AMP 01:01:51]): __________

## 1. What truth are we trying to see?

Metrics are proxies for “some truth” [PVP 29:35]. In one sentence, what do we want to know?

> ___________________________________________

## 2. One row per category

| Category | Metric(s) | Why it matters here | Where it lives | Instrumented? |
|---|---|---|---|---|
| Health (latency, uptime, errors [PVP 33:25]) | | | | Y / N |
| Usage (how it's used, what users do [AMP 01:01:51]) | | | | Y / N |
| Adoption | | | | Y / N |
| Satisfaction | | | | Y / N |
| Ecosystem | | | | Y / N |
| Outcome | | | | Y / N |

Not every category needs a metric for every product. Leave a row blank only on purpose.

## 3. The 1 to 3 we manage to

He advises clarity on "the 1-3 metrics you are focused on, why they matter" [X 2024-01-10], tied to the
initiatives that move them.

| Metric | Initiative that moves it | Short / medium / long term |
|---|---|---|
| | | |

## 4. Treat the dashboard as a product [AMP 01:01:51]

- [ ] Usage is instrumented before we call it feature-complete [X 2021-04-27].
- [ ] The dashboard has a view counter.
- [ ] A summary email with a few top-line stats and a link goes out (cadence: ______).
- [ ] The dashboard is pinned for the people who decide.
- [ ] **Our suggestion:** after 30 days, check the view count. If nobody looks, either it isn't useful or
      there's friction to fix.
