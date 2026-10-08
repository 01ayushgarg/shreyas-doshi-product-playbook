# 02 · Pre-mortems

> "If you do a pre-mortem right, you will not have to do an ugly post-mortem." [L1 00:24:50]

He calls a well-run pre-mortem "among the highest ROI things you can do when working on an important project
or launch" [X 2023-05-03](https://x.com/shreyas/status/1653830492825985024), and "one of those very low
downside, but very high upside things." [L1 00:33:00]

**Background (ours, not his):** the pre-mortem is an older decision technique that he did not invent and
doesn't claim to. Our sources don't name its originator, so we don't credit one on his behalf. What is his is
the version below: the tiger, paper tiger and elephant vocabulary, the quiet-time format, and the vote on
someone else's tiger.

## The prompt is the genius

> "The genius of the pre-mortem ritual is the initial prompt." [L1 00:24:50]

The prompt: "imagine this project that we are working on has failed six months from now, or this launch we
are doing has miserably failed" [L1 00:24:50], and ask everyone why.

Why it works: it gives "much greater psychological safety for team members to talk about things they're
concerned about." [L1 00:25:47] He also notes the mood afterwards: people feel lighter, because it is a
catharsis to finally say these things. [L1 00:26:40]

## Tigers, paper tigers and elephants

Each person brings up three kinds of thing, in a shared doc. [L1 00:27:14]

| Category | In his words |
|---|---|
| **Tiger** | "a tiger is a threat that will actually kill us, just like a tiger would" [L1 00:27:14] |
| **Paper tiger** | "this is a seeming threat that others might be worried about, but you're not worried about" [L1 00:27:51] |
| **Elephant** | "the elephant in the room that nobody is talking about" [L1 00:27:51] |

> "Perhaps the best part about a pre-mortem is that shared vocabulary." [L1 00:28:28]

## How he runs the meeting

1. **He shares the prompt** as the meeting leader. [L1 00:30:35]
2. **Quiet time.** He alternates speaking and quiet time: "the next five minutes or the next 10 minutes is
   quiet time", while people enter their tigers, paper tigers and elephants in the template where nobody
   else sees them. Then they go around the room and share. [L1 00:30:35]
3. **Vote on someone else's tiger.** People "pick the tiger that they find more scary, but that somebody else
   mentioned." [L1 00:31:11]
4. **Prioritize, don't solve everything.** "The point is not to solve every problem, the point is to identify
   threats that we are not talking about openly." [L1 00:31:11]
5. **Close the loop.** "Create a pre-mortem action plan and then share that with the team and keep myself as
   the leader accountable for actually making progress on it." [L1 00:31:11]

For big launches, "I like doing a separate pre-mortem for the go-to-market side." [L1 00:30:07]

## When to run one

> "If you aren't doing pre-mortems for major products and initiatives, you're almost certainly doing it
> wrong." [X 2020-08-23](https://x.com/shreyas/status/1297376205121835009)

"Pre-mortems for big launches" is also on his list of high-leverage meetings from leading products at Stripe.
[X 2023-05-03](https://x.com/shreyas/status/1653611053442555904)

**On cost, read the context.** His "Pre-mortems literally take 1-2 hours" line comes from a post about one
case: a major player changing its terms of service, where he says privacy changes are always meaningful.
[X 2023-08-09](https://x.com/shreyas/status/1689306193771237376) It is not a general claim about every
launch. On the podcast he mentions a pre-mortem session of "say 30 minutes or an hour". [L1 00:26:40]
**Our reading:** budget one to two hours for a big launch, less for a small change.

## How to apply it (our reading)

**Worked scenario (invented):** a 12-person team is eight weeks from launching usage-based pricing. The
pre-mortem surfaces 31 items. Votes cluster on two tigers: invoices that customers can't reconcile, and
support not trained on the new plans. One paper tiger (a competitor's price cut) is dropped. The elephant
nobody had said aloud: the billing engineer is the only person who understands the metering code. The action
plan has three owners and dates, and the leader reviews it in every weekly team review until launch.

**Failure modes (our reading):**
- Running it after the plan is locked, so nothing can change.
- The leader speaking first, which anchors everyone.
- Treating every item as a must-fix. His point is to surface threats, then prioritize.
- No owner for the action plan, so it dies in the doc.
- Skipping the go-to-market pre-mortem on a big launch.

**Limits:** a pre-mortem finds risks people already sense. It won't find a risk nobody in the room can
see, which is a reason to invite go-to-market, support or sales for big launches.

**Use it now:** `templates/02-pre-mortem-kit.md`.

**Checks to run:**
1. What launch or bet in the next 3 months would hurt most if it failed? Has it had a pre-mortem?
2. After the last pre-mortem: is the action plan shared, and is anyone tracking it?
3. Which elephant do you already suspect nobody will say out loud?
