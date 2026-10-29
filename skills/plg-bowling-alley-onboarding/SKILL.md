---
name: plg-bowling-alley-onboarding
description: Audit and redesign user onboarding with the Bowling Alley Framework — map every step to the First Strike, cut or delay steps (green/yellow/red + DAD test), reorder and simplify, add profiling questions, segment by job, and add product bumpers and conversational bumpers. Use for activation problems, signups that never return, long time-to-value, signup forms, or onboarding flows.
---

# Bowling Alley Onboarding (Straight Line + Bumpers)

40–60% of signups use a product once and never return. Goal: effortless to sign up, to reach value, to upgrade. Picture a bowling lane: the straight line gets the ball to the pins (the **First Strike** = first experience of core value); bumpers keep it out of the gutters.

Prereqs: a named First Strike (`plg-user-endgame`) and ideally the user's job (`plg-jtbd-outcomes`). If none exists, define the First Strike first: the action that delivers the outcome they signed up for (export a design, host a meeting, send an invoice).

## Phase 1 — Straight-line onboarding
1. **Map the path** from the very first touchpoint (search result, ad, invite email) to the First Strike. Sign up as a brand-new user. Every field and click is a step — 10 form fields + submit = 11 steps. Screenshot each. (Later iterations: map to the KUI, then to Upgrade.)
2. **Add profiling questions** right after signup (as few as possible): which question tells me if this is an ideal user? which lets me drop them straight into the right place? Use answers to personalize.
3. **Label every step** (team labels individually first, then discusses):
   - 🟢 Green — required to reach the First Strike now
   - 🟡 Yellow — needed eventually; delay until after the First Strike
   - 🔴 Red — remove
   Usual suspects: email confirmation before entering the product (often loses 10–30% of signups), manual "save" (use autosave), typing invitees one by one (use a share link), nickname/avatar/settings.
   **DAD test** — keep friction that **D**irects them toward the First Strike, **A**dds personalization, or **D**elights (IKEA effect: e.g. upload a logo and instantly see a branded invoice).
4. **Order by ease**: easiest first (name before email). Let users invest work before asking for an account ("create an account to save your invite").
5. **Simplify**: fewer choices; progressive disclosure (show a field only when relevant); split long forms into short pages, heaviest last.
6. **Finalize** the straight line = green steps only, agreed by product, engineering, marketing and support. Typical result: 30–40% of steps cut, ~20% delayed, value 2–3x easier to reach.
7. **Segment**: if users hire the product for different jobs, build one straight line per job (separate lanes), chosen by the profiling answers or by use-case landing pages that open the product in the right spot.

## Phase 2 — Product bumpers (in-app; add only where data shows drop-off)
- Welcome message — restate value, set expectations
- Product tour — few options, route by goal; explain *why*, not a tour of every button
- Progress bar and checklist — pre-fill the first item
- Tooltips — only for straight-line steps; hotspots for optional discovery
- Empty states — show what success will look like + one CTA toward it; avoid fake data unless it teaches (a sample project)
- Templates/cheat sheets so nobody starts from a blank page
Bumpers are not a bandage for a bad flow — fix the line first.

## Phase 3 — Conversational bumpers (out of app)
Care continuum, hands-off → hands-on: external messages (email, SMS, LinkedIn, post) · knowledge base · in-app chat · community · training (live calls, academy, cohorts — closes knowledge gaps) · specialists (technical or sales).
Match intensity to customer value. Start with a **VIP experience**: hand-hold every new signup for a few weeks (personal welcome, onboarding call, trial extension, manual setup), note what makes them succeed, then automate that. The unscalable path reveals the scalable one. Coach, don't helicopter.
For the message plan itself, run `plg-onboarding-prompts`.

## Output
Before/after step table (step · colour · action · reason) · step count and estimated time-to-value before/after · profiling questions · product bumpers per drop-off point · conversational bumper plan · test plan (split-test, compare retention).

Source: *The Product-Led Playbook* (Wes Bush) ch. 5 and *Product-Led Onboarding* (Ramli John) ch. 7. Unofficial summary.
