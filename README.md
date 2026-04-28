# 🛒 E-commerce & Retail Skills Suite
### Derived from [alirezarezvani/claude-code-skill-factory](https://github.com/alirezarezvani/claude-code-skill-factory)

![Domain](https://img.shields.io/badge/Domain-E-commerce%20&%20Retail-orange?style=for-the-badge)
![Commands](https://img.shields.io/badge/Commands-10-blue?style=for-the-badge)
![Workflows](https://img.shields.io/badge/Workflows-5-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> **Adaptation of `alirezarezvani/claude-code-skill-factory` for E-commerce & Retail use cases.**
> Source focus: _skill scaffolding, code agents, slash command generation_

---

## What This Skill Suite Does

Product catalogue optimisation, conversion rate, customer journey and retail analytics.

This collection provides **10 specialised commands** and
**5 multi-step workflows**, all with a consistent
structured-output UI so you always know exactly where you are and what to do next.

---

## Quick Install

```bash
# Clone this skill
cp -r . ~/.claude/skills/r00-alirezarezvani-claude-code-skill-factory--ecommerce/

# Register in Claude Code
# In a Claude Code session:
/read ~/.claude/skills/r00-alirezarezvani-claude-code-skill-factory--ecommerce/SKILL.md
```

---

## Commands

| Command | Description |
|---------|-------------|
| `/product-copy` | Conversion-optimised product title, description and bullet points from spec sheet |
| `/price-strategy` | Dynamic pricing recommendation using competitor data and elasticity model |
| `/cart-abandonment` | Cart abandonment email sequence with personalisation tokens and timing logic |
| `/inventory-forecast` | Demand forecasting report with reorder points and safety stock calculation |
| `/cro-audit` | CRO heatmap analysis, funnel drop-off diagnosis and A/B test prioritisation |
| `/customer-segment` | RFM segmentation, LTV prediction and targeted campaign briefs |
| `/returns-analysis` | Return rate root-cause analysis with product quality and size-guide fixes |
| `/review-response` | AI-generated personalised responses to product reviews (positive + negative) |
| `/bundle-suggest` | Cross-sell and bundle recommendation engine from order history patterns |
| `/marketplace-audit` | Amazon/eBay listing health score, Buy Box eligibility and keyword gap |

**Usage:**
```bash
/product-copy <target>
/price-strategy --scope full --output md
```

---

## Workflows (Multi-step)

| Workflow | Description |
|----------|-------------|
| `product-launch` | Full product launch: copy → imagery brief → ads → email → SEO → review plan |
| `seasonal-campaign` | Black Friday / holiday campaign: offer → landing page → email sequence → ads |
| `retention-engine` | Post-purchase flow: confirmation → onboarding → loyalty → win-back sequence |
| `marketplace-expand` | New marketplace expansion: listing → pricing → fulfillment → compliance checklist |
| `conversion-sprint` | 90-day CRO sprint: audit → hypothesis → A/B tests → iterate → report |

**Usage:**
```bash
/workflows:product-launch <target> --scope full
```

---

## UI Design

All commands display structured output with:

- **Progress panels** — real-time step tracking
- **Findings tables** — sorted by severity (🔴🟠🟡🟢)
- **Action checklists** — quick wins → medium-term → strategic
- **Summary cards** — at-a-glance metrics after each command


## Progress Display Example

```
╔══════════════════════════════════════════════════╗
║  Product Launch  —  Wireless Headphones Pro X    ║
╠══════════════════════════════════════════════════╣
║  ✓  Product copy generated      3 variants ready ║
║  ✓  SEO keywords mapped         42 terms         ║
║  ⟳  Image briefs in progress …  2 / 8            ║
║  ░  Ad creatives                Pending           ║
║  ░  Email sequence              Pending           ║
╚══════════════════════════════════════════════════╝

Conversion Score:  ████████░░  78 / 100
┌────────────────────┬───────┬─────────────────────────┐
│ Element            │ Score │ Recommendation           │
├────────────────────┼───────┼─────────────────────────┤
│ Title (SEO)        │  92   │ ✓ Good                  │
│ Bullet points      │  74   │ ⚠ Add 2 more benefits   │
│ Price anchor       │  61   │ ✗ Add original price     │
│ Social proof       │  88   │ ✓ 4.7★ visible          │
│ CTA button         │  70   │ ⚠ Test "Buy Now" copy   │
└────────────────────┴───────┴─────────────────────────┘
```


---

## Interaction Pattern

Every command follows this 5-step structure:

```
① Scope Confirmation  — verify target and options with user
② Live Analysis       — progress bar while working
③ Findings Table      — structured results sorted by impact
④ Action Plan         — prioritised, time-boxed recommendations
⑤ Next Steps          — suggested follow-up commands
```

---

## Source Repository

This suite is derived from
**[alirezarezvani/claude-code-skill-factory](https://github.com/alirezarezvani/claude-code-skill-factory)**
which focuses on: _skill scaffolding, code agents, slash command generation_.

Improvements in this adaptation:
- Domain-specific command vocabulary for E-commerce & Retail
- Enhanced structured output with visual progress tracking
- Prioritised action plans with time estimates
- Workflow orchestration for end-to-end processes
- Consistent UI conventions across all commands

---

## License

MIT — free to use, modify and distribute.
