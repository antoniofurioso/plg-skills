---
name: plg-advisor
description: Entry point for product-led growth work on any business. Use when someone asks for PLG help in general ("make us product-led", "why aren't people upgrading", "where do we start"), or when it's unclear which PLG framework applies. Diagnoses the biggest bottleneck and routes to the right plg-* skill.
---

# PLG Advisor (router)

Diagnose where a business is stuck and run the right framework. Works for SaaS, services, education, marketplaces, apps — anything where people can experience value before paying.

Core belief behind every skill in this set: a product sells itself when the user reaches real value fast enough to believe in it. Time-to-value is the thread through everything.

## Step 1 — Gather context (ask only what's missing)

- What the business sells, to whom, at what price (rough ACV / monthly price)
- How people buy today: demo/call only, free trial, freemium, paid only
- Rough funnel numbers if they exist: visitors → signups → activated → paying
- Website URL (fetch the homepage and pricing page if available)
- What they think the problem is

If the person can't give numbers, proceed on qualitative evidence and say which numbers to start tracking.

## Step 2 — Place them in the system

Use this order. The first broken layer is the bottleneck; fixing later layers first wastes effort (e.g. polishing onboarding when the homepage converts 0.05% of visitors).

| Question | If the answer is "no" or "unclear" → use |
|---|---|
| Should this business be product-led at all, and in what flavour? | `plg-moat-readiness` |
| Is the leadership/team actually ready (belief, priority, skills)? | `plg-preflight-check` |
| What competitive level are they at and what's the next move? | `plg-market-ascent` |
| Is there a clear strategy, niche and set of moats? | `plg-bullseye-strategy` |
| Do they know their ONE ideal user and that user's journey? | `plg-user-endgame` |
| Do they know why people really sign up (jobs, push/pull)? | `plg-jtbd-outcomes` |
| Is the free experience designed on purpose (what's free vs paid)? | `plg-free-model` |
| Does the homepage/offer convert visitors into signups? | `plg-irresistible-offer` |
| Do signups reach first value fast (minimal steps, bumpers)? | `plg-bowling-alley-onboarding` |
| Are there behaviour-triggered messages that pull users back? | `plg-onboarding-prompts` |
| Do they know the action that predicts retention? | `plg-adoption-indicator` |
| Does pricing scale with value and read in 5 seconds? | `plg-value-ladder-pricing` |
| Is there a weekly scorecard that shows the bottleneck? | `plg-true-north-scorecard` |
| Is there a meeting rhythm that turns the bottleneck into projects? | `plg-growth-process` |
| Is the team lean, accountable and growing? | `plg-elite-team` |
| Do they need sales on top of self-serve (PQLs, expansion)? | `plg-product-led-sales` |

Shortcut when funnel data exists: find the biggest relative drop.
- Visitors → signups weak → offer / homepage
- Signups → setup or first value weak → onboarding (bowling alley, prompts)
- First value → repeat use weak → adoption indicator, prompts, free model
- Active → paid weak → free model, pricing, product-led sales
- Paid → retained/expanding weak → user endgame (Scale stage), adoption indicator

## Step 3 — Output

Give a short diagnosis:
1. Bottleneck (one sentence, with the evidence)
2. Which skill to run now and why
3. What to leave alone for now (be explicit — focus is the point)
4. Then run that skill.

## Onboarding projects (EUREKA order)

When the problem is clearly onboarding, run in this order: set up a cross-functional team with an executive sponsor (product, marketing, success, sales — one person "champions", everyone contributes) → `plg-jtbd-outcomes` → `plg-adoption-indicator` → `plg-bowling-alley-onboarding` → `plg-onboarding-prompts` → ship changes as small experiments.

Experiment loop for any change: Analyze (which input drives the outcome) → Ask (where do we want to go, which levers, which input to invest in) → Act (ship one). Prioritize on impact × effort: quick wins first, big bets planned, small momentum builders when cheap, skip high-effort/low-impact. Split-test where traffic allows; compare retention curves, not just clicks. Share every result with the whole company. After initial onboarding works, onboard users **deeper** (advanced use of the same job) or **wider** (adjacent jobs) to drive expansion.

## Source

Frameworks from the free online books by Wes Bush and Ramli John at productled.com/library: *Product-Led Growth*, *The Product-Led Playbook*, *Product-Led Onboarding*. Unofficial summary in our own words.
