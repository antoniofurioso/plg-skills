# plg-skills

Agent skills (Claude / Claude Code `SKILL.md` format) that turn the product-led growth frameworks from the three free ProductLed books into step-by-step workflows you can run on any business: SaaS, services, apps, marketplaces, education.

> **Unofficial.** Not affiliated with or endorsed by ProductLed, Wes Bush or Ramli John. These skills summarize the frameworks in our own words and link to the originals. Read the books, they're free:
> - [Product-Led Growth](https://productled.com/book/product-led-growth) — Wes Bush
> - [The Product-Led Playbook](https://productled.com/book/playbook) — Wes Bush
> - [Product-Led Onboarding](https://productled.com/book/onboarding) — Ramli John

## Skills

| Skill | Use it for | Source |
|---|---|---|
| `plg-advisor` | Start here: finds the bottleneck and routes to the right skill | All three |
| `plg-moat-readiness` | Should we be product-led? Cost of Proof, spectrum, MOAT flags | PLG ch. 3–5 |
| `plg-preflight-check` | Org readiness: Conviction, Commitment, Capabilities, Construction, Cash | PLG ch. 6 |
| `plg-market-ascent` | Commodity → Contender → Cusp → Chosen → Cause; PLG 1.0/2.0/3.0 | PLG intro, ch. 7 |
| `plg-bullseye-strategy` | Niche, 15 moats, endgame, strategic no's → One-Page Endgame | Playbook ch. 1 |
| `plg-user-endgame` | One ideal user + 5-stage journey, First Strike, KUI | Playbook ch. 2 |
| `plg-free-model` | What's free vs paid (DEEP), trial vs freemium vs usage-based | Playbook ch. 3 |
| `plg-irresistible-offer` | Homepage/offer: Result, Advantage, Assurance, 5 sections | Playbook ch. 4 |
| `plg-bowling-alley-onboarding` | Straight-line onboarding + product/conversational bumpers | Playbook ch. 5, Onboarding ch. 7 |
| `plg-onboarding-prompts` | Behaviour-triggered emails and in-app nudges (BJ Fogg) | Onboarding ch. 8 |
| `plg-jtbd-outcomes` | Why users sign up: jobs, four forces, interview script | Onboarding ch. 5 |
| `plg-adoption-indicator` | Find the retention "magic number" from data | Onboarding ch. 6 |
| `plg-value-ladder-pricing` | Value metric, pricing matrix, price research, pricing page | Playbook ch. 6 |
| `plg-true-north-scorecard` | North Star, funnel metrics, weekly scorecard, PQLs | Playbook ch. 7 |
| `plg-growth-process` | Quarterly / monthly / weekly meeting rhythm | Playbook ch. 8 |
| `plg-elite-team` | Accountability chart, audits, incentives, development | Playbook ch. 9 |
| `plg-product-led-sales` | PQL scoring, qualification matrix, when sales reaches out | Onboarding ch. 10, PLG ch. 4 |

Suggested order for a new product: readiness → strategy → user → free model → offer → onboarding → pricing → scorecard → process → team.

## Install

**Claude Code** — copy the skills into your skills folder:
```bash
git clone https://github.com/<your-username>/plg-skills.git
cp -r plg-skills/skills/* ~/.claude/skills/
```
**Claude.ai** — zip a skill folder (e.g. `skills/plg-free-model`) and upload it in Settings → Capabilities → Skills.

## Example prompts
- "Use plg-advisor on example.com — signups are fine but nobody upgrades."
- "Run plg-free-model for my Polish grammar app."
- "Audit this homepage with plg-irresistible-offer: <url>"
- "Here's our events export (CSV). Find our product adoption indicator."

## License
MIT for the skill files in this repo. The underlying frameworks and book content belong to their authors.
# plg-skills
