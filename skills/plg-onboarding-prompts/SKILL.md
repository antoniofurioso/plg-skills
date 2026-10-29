---
name: plg-onboarding-prompts
description: Design behaviour-based onboarding messages (email, in-app, SMS) and engagement nudges using the BJ Fogg model (motivation × ability × prompt) — welcome messages, progress, celebrations, social proof, and a milestone-triggered email flow. Use for onboarding email sequences, trial nurture, re-engaging inactive signups, or "users sign up and disappear".
---

# Keep Users Engaged: Behaviour-Based Prompts

A behaviour happens when **Motivation**, **Ability** and a **Prompt** meet. If users drop off, ask: is the next step easy enough? do they want it enough? did something prompt them at the right time? Prompts only work when motivation and ability are high enough.

## 1. Make it easy (ability)
- Avoid cognitive overload: one thing at a time.
- Visual cues pointing to the next step; short guided tours over tooltip storms.
- Empty states that show the future and one action.
- Templates, examples, cheat sheets, copy-paste starters.

## 2. Raise motivation (intrinsic, not bribes)
Don't reward onboarding completion with badges or trial extensions — it attracts people who want the reward, not the product.
- Copy that speaks to desires and objections at every step ("get paid 3x faster"), not features.
- Progress indicators and checklists (unfinished lists pull people back).
- A welcome that bonds: short founder video or note, shared mission, what to expect, how to get help — from a reply-able address, never "no-reply".
- Celebrate wins: first result, first publish, upgrade recap; occasionally a delightful physical gesture.
- Social proof near CTAs and friction points, tied to objections, with real names/faces/companies — in app and email.

## 3. Behaviour-based prompts
Prompts matter at two moments: signup → first value, and first value → habit. Rules: multi-channel (always include email), triggered by what users did or didn't do (not a fixed time drip), and always restating value. Segment by job later; start with one path.

### Build the flow
1. **List milestones** of the straight line (`plg-bowling-alley-onboarding`): signed up · each critical setup step · First Strike · repeat use · trial start / days before end / end / after.
2. **For each milestone, ask "why might someone NOT do this?"**
   - Low motivation → value reminder, pain of the status quo, case study.
   - Low ability → template, short tutorial, help article, offer of a quick call.
   Each milestone gets: success branch (congratulate + next step) and fallback branch (1–2 nudges, then a human offer).
3. **Fill in details**: one primary CTA per message · personal, human tone · short and scannable, a visual if useful · mobile-first subject and preview · segment where you can.

Message types to draw from: welcome · usage tip · value reminder · case study · celebration · trial-ending warning · trial-extension offer (often converts) · personal sales/success touch for high-value accounts (`plg-product-led-sales`).

## Output
Flow table: trigger (event or non-event + delay) → channel → goal → subject/preview → body draft → CTA. Plus the in-app motivation elements to add. Note which tools can trigger on product events (e.g. Customer.io, Userlist, Intercom, Loops).

Source: *Product-Led Onboarding* (Ramli John), ch. 8. Unofficial summary.
