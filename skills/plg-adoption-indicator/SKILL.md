---
name: plg-adoption-indicator
description: Define onboarding success milestones (signup, First Strike, Product Adoption Indicator) and find the retention-predicting "magic number" from product data with a 5-step method — baseline cohort retention, hypothesis, threshold testing, curve comparison, rollout. Use for activation metrics, "aha moment", magic number, what counts as an activated user, or analysing retention/event exports.
---

# Product Adoption Indicator (PAI)

Three moments define onboarding success:
1. **Value perception** — signup (more friction = stronger intent signal: card-required trials can convert up to ~60% but get far fewer starts; no-card trials get more starts at ~5%+).
2. **Value experience** — the **First Strike**: the necessary action that delivers the user's desired outcome (export a design, host a call; for networks, adding a friend). Multi-use products have one per job.
3. **Value adoption** — the **PAI**: the point after which users are very likely to keep using it (7 friends in 10 days; a team's 2,000 messages).

## A good PAI
- Leading indicator of retention
- Repetition of ONE key action (habits come from repetition)
- Simple enough that everyone in the company can say it
- Time-bound ("within the first N days")
- Happens early in the journey

## 5 steps to find it (needs per-user event data)
1. **Baseline retention**: cohort by signup day/week; retention(day d) = users active on day d ÷ cohort size × 100. Plot the curve and note where it flattens (Z).
2. **Hypothesis**: "Users who do ≥X [key action] within the first Y days are more likely to still be active after Z days."
3. **Test thresholds**: for X = 1, 2, 3…, count:
   - A: retained AND did ≥X
   - B: retained AND did < X
   - C: not retained AND did ≥X
   Pick the X that maximizes overlap, e.g. A ÷ (A+B+C). Too high a threshold misses many retained users; too low includes many churners.
4. **Validate**: plot the retention curve of users who hit the PAI vs the baseline; it should be clearly higher (optionally run a logistic regression).
5. **Communicate**: one sentence, company-wide. Marketing optimizes for PAI-reaching signups, not raw signups; success/sales give extra care to those approaching it.

If the user uploads CSV/event exports, run the analysis in code and show the threshold table and both curves. If there's no data yet (new product): define the First Strike, get as many users to it as possible, and instrument events now.

## Instrumentation
Basic web analytics isn't enough; use product analytics with per-user events (Mixpanel, Amplitude, PostHog, Heap…). List the 5–8 key engagement events for this product (e.g. project created, task completed, teammate invited, file uploaded).

## PAI vs PQL
A PQL (`plg-product-led-sales`) can combine several signals and sit anywhere between signup and PAI depending on sales capacity: more reps → lower bar.

## Output
Milestones (signup, First Strike per job, PAI) · baseline curve · threshold table · chosen PAI sentence · events to track · how each team uses it.

Source: *Product-Led Onboarding* (Ramli John), ch. 6. Unofficial summary.
