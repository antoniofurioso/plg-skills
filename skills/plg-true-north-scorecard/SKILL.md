---
name: plg-true-north-scorecard
description: Build a weekly growth scorecard with the True North Framework — a North Star Metric, six go-to-market funnel metrics, business health metrics, metric owners, and Product Qualified Leads — to always know the #1 bottleneck. Use for KPI selection, North Star Metric, funnel diagnosis, dashboards/scorecards, metric ownership, or "where is our bottleneck?".
---

# True North Scorecard

You won't talk to most users in a product-led business; behaviour data is how you hear them. Find the real bottleneck before fixing anything (a team that spent a quarter on onboarding when 7,300 visitors produced 4 signups was fixing the wrong thing).

Traps: tracking everything (36 metrics = no focus) · no owner · vanity metrics · unsegmented data (mixing ideal and non-ideal users hides the truth).

## Phase 1 — Pick the metrics
**North Star Metric (one)** = quality action × quantity × frequency, where the user getting more value also earns the company more (Slack: messages/week; Airbnb: nights booked/month; DocuSign: documents signed/week).
Criteria: easy to measure · tracks the user endgame · best customers do it a lot · fits the strategy. Candidates: the value metric, the Key Usage Indicator, what highest-LTV and best-retained users repeatedly do. Choose a frequency matching natural usage (weekly for work tools, daily for social).

**Go-to-market metrics (six)**: unique visitors → signups → setup completed → First Strike → Key Usage Indicator → upgrades. The biggest relative drop is the bottleneck:
- visitors→signups → `plg-irresistible-offer`
- signups→setup/First Strike → `plg-bowling-alley-onboarding`, `plg-onboarding-prompts`
- First Strike→KUI → `plg-adoption-indicator`, `plg-free-model`
- KUI→upgrade → `plg-value-ladder-pricing`, `plg-product-led-sales`
Track what you can; don't add extras.

**Business health (three)**: MRR · total revenue churn · cash balance (weekly — revenue can grow while cash doesn't). Optional: net revenue retention, expansion MRR, average revenue per customer, CAC.

## Phase 2 — Weekly scorecard
A simple shared spreadsheet: one row per metric, weekly columns, target, owner, status. Filled in manually by owners (it forces thinking).
- **Ownership test** per metric: can they move it a lot? do they want it? do they have capacity?
- Backfill last month before setting targets.
- Weekly review; the owner of an off-track metric becomes "CEO for the week" and can pull help from everyone.
- Praise publicly when targets are hit.
Statuses: on track · trending on track · off track with plan · off track no plan · off track, target unreachable.

## Phase 3 — Product Qualified Leads (after ~1 month of scorecard)
**PQL = ideal user profile + setup completed + First Strike + Key Usage Indicator.** Expect high upgrade odds (often cited ~30–50%).
Upgrade the scorecard: signups → *ideal* signups · KUI → PQLs · upgrades → *ideal-user* upgrades. Every team contributes to PQLs.

## Output
NSM with rationale · GTM metric definitions + current numbers + conversion rates · bottleneck call-out · health metrics · scorecard template (CSV/sheet) with owners and targets · PQL definition.
If data is supplied, compute conversions in code and build the sheet.

Source: *The Product-Led Playbook* (Wes Bush), ch. 7. Unofficial summary.
